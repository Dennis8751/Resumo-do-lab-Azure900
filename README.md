# Resumo-do-lab-Azure900
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
# **Microsoft - Azure AZ-900**

O **AZ-900** é uma **porta de entrada** para o mundo do Azure, dando visão geral dos **conceitos de nuvem, serviços principais e modelos de preços/segurança**.

## Computação em nuvem

- **O que é computação em nuvem**
    
    É a entrega de recursos de TI (servidores, armazenamento, rede, aplicativos) pela internet, de forma sob demanda, pagando apenas pelo que usar.s
    
- **Responsabilidade compartilhada**
    - **Microsoft/Azure**: gerencia a infraestrutura da nuvem (datacenters, hardware, rede física).
    - **Cliente**: gerencia dados, identidade, aplicações e configurações dentro da nuvem.
        
        (O nível varia conforme IaaS, PaaS ou SaaS).
        
- **Modelo de nuvem**
    - **Pública**: recursos compartilhados e acessados pela internet (ex: Azure).
    - **Privada**: infraestrutura exclusiva para uma empresa. As organizações criam um ambiente em nuvem em seu datacenter e são responsáveis por operar os serviços que fornecem. Não fornece acesso aos usuários fora da organização.
    - **Híbrida**: mistura das duas (pública + privada) pra permitir que os aplicativos sejam executados no local mais adequado.
- **Custo de capital versus custo operacional**
    - **CapEx**: investimento inicial alto em hardware, software e datacenter próprios.
    - **OpEx**: gastos variáveis conforme uso, pagando sob demanda (modelo da nuvem).

### Comparação de modelos de nuvem

- **Nuvem Pública**
    - Nenhuma despesa de capital para escalar verticalmente.
    - Os aplicativos podem ser provisionados e desprovisionados rapidamente.
    - As organizações pagam apenas pelo que utilizam
- **Nuvem Privada**
    - As organizações têm controle total sobre os recursos e a segurança.
    - As organizações são responsáveis pela manutenção e pelas atualizações de hardware e software.
- **Nuvem Hibrida**
    - As organizações determinam onde executar seus aplicativos.
    - As organizações controlam a segurança, a conformidade e os requisitos legais.
    - Fornece a maior flexibilidade.

### Comparação CapEx e OpEx

- **Despesas de capital (CapEx)**
    - O gasto inicial de dinheiro em infraestrutura física.
    - As despesas do CapEx têm um valor que se reduz com o tempo.
- **Despesas operacionais (OpEx)**
    - Gastar com produtos e serviços conforme necessário, pagando conforme o uso.
    - Seja cobrado imediatamente.
## Benefícios da Nuvem

- Alta disponibilidade
    
    A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer (SLA). Caso haja uma indisponibilidade além do prazo esperado, o cliente recebe um crédito (voucher).
    
- Escalabilidade
    - A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda.
    - A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
    - Outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços.
    - Com a escala vertical. se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.
- Elasticidade
    - Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente).
    - Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão.
    - Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).
- Confiabilidade
    - Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente.
    - Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo.
- Previsibilidade
    - A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework.
- Segurança
    - A nuvem oferece ferramentas de segurança que atendem às necessidades dos cliente mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.
    - Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.
- Governança
    - A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação(resolução de problemas).
    - Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
    - Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.
- Gerenciabilidade
    - Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambos trazem excelentes benefícios.
    - O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Por exemplo:
        - Escalar automaticamente a implantação de recursos com base na necessidade.
        - Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
