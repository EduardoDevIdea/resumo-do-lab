# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO sobre Microsoft Azure

Fornecede serviços de computação pela internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala.

Nuvem privada 
•	As organizações criam um ambiente em nuvem em seu datacenter
•	As organizações são responsáveis por operar os serviços que oferecem
•	Não fornece acesso aos usuários fora da organização
•	As organizações têm controle total sobre recursos e a segurança
•	As organizações são responsáveis pela manutenção e pelas atualizações de hardware

Nuvem pública
•	Pertencente a serviços de nuvem ou provedor de hosting
•	Fornece recursos e serviços a várias organizações e usuários
•	Acessada via conexão de rede segura (geralmente pela internet)
•	Nenhuma despesa de capital (CapEx) para escalar verticalmente
•	Os aplicativos podem ser provisionados e desprovisionados rapidamente
•	As organizações pagam apenas pelo que utilizam

Nuvem híbrida
•	Combina nuvens públicas e privadas para permitir que os aplicativos sejam executados no local mais adequado
•	As organizações determinam onde executar seus aplicativos
•	As organizações controlam a segurança, a conformidade e os requisitos legais
•	Fornece maior flexibilidade

Despesas de Capital - CapEx
•	O gasto inicial de dinheiro em infraestrurura física
•	As despesas do CapEx têm um valor que se reduz com o tempo
Despesas operacionais – OpEx
•	Gastar com produtos e serviços conforme necessário, pagamento conforme o uso
•	Seja cobrado imediatamente

Modelo baseado em consumo
•	Os provedores de serviços em nuvem operam em um modelo baseado no consumo, o que significa que os usuários finais pagam somente pelos recursos que usam
•	Melhor previsão de custos
•	São fornecidos preços para recursos e serviços individuais
•	A cobrança é feita com base no seu uso real

Benefícios da nuvem
•	Alta disponibilidade: se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.
•	SLA
•	Escalabilidade: refere-se à capacidade de ajustar recursos para atender à demanda. Você poderá adicionar mais recursos para lidar melhor com o aumento da demanda. Paga apenas o necessário pelos serviços. Se a demandar cair, poderá reduzir seus recursos e, assim, reduzir seus custos. Com a escala vertical, caso precise de mais processamento, poderá escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.
•	Elasticidade: em caso de um salto repentino acentuado na demanda, os recursos implantados poderiam ser expandidos (automaticamente ou manualmente)
•	Confiabilidade:  devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. A nuvem permite que você tenha recursos implantados em várias regiões do mundo. Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.
•	Previsibilidade: permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well Architected Framwork.
•	Segurança: oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente. Se quiser controle máximo de segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.
•	Governança: a auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. Dependendo do modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança. Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter a sua presença de nuvem atualizada, protegida e bem gerenciada.
•	Gerenciabilidade: um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento; Escalar automaticamente a implantação de recursos com base na necessidade; Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual; O gerenciamento da nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos por exemplo: por meio de um portal web, usando uma interface de linha de comando, usando APIs, usando PowerShell

Tipos de Serviços em Nuvem na Azure

IaaS (Infraestrutura como Serviço)
•	Infraestrutura de TI conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.
•	Servidores e armazenamento; Firewalls/Segurança; Planta física/edifício do datacenter
•	O serviço de nuvem mais flexível
•	Você configura e gerencia o hardware para seu aplicativo

PasS  (Plataforma como serviço)
•	Engloba IaaS: Servidores e armazenamento; Firewalls/Segurança; Planta física/edifício do datacenter
•	Possui Sistemas operacionais, Ferramentas para desenvolvedores, análise de negócios de gerenciamento de database.
•	Fornece um ambiente para a criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente.
•	Focado no desenvolvimento de aplicativos
•	O gerenciamento de plataforma é realizado pelo provedor de nuvem

SaaS (software como  serviço)
•	Engloba IaaS e PaaS
•	Possui Aplicativos/apps hospedados 
•	Exemplo: Microsoft Teams
•	Os usuparios se conectam e usam aplicativos com base em uma nuvem pela internet: por exemplo, Microsoft Office 365, e-mails, calendários
•	Modelo de preço de pagamento conforme o uso
•	Os usuários pagam pelo software que utilizam em modelo de assinatura

Principais componentes arquitetônicos do Azure

•	Descrever regiões, pares e regiões soberanas do Azure.
•	Descrever as zonas de disponibilidade
•	Descrever os datacenters do Azure
•	Descrever os recursos e os grupos de recurso do Azure
•	Descrever as assinaturas
•	Descrever os grupos de gerenciamento
•	Descrever a hierarquia de grupos de recursos, assunaturas e grupos de gerenciamento

Contas do Azure
•	Conta Azure
•	Conta gratuita do Azure
•	Conta de estudante gratuita do Azure
•	Área restrita do Microsoft Learn

Regiões
•	O Azure oferece mais regiões globais do que qualquer outro provedor de nuvem, com mais de 60 regiões representando mais de 140 países.
•	As regiões são compostas de um ou mais datacenters muito próximos
•	Eles fornecem flexibilidade e escala para reduzir a latência do cliente
•	As regiões preservam a residência dos dados com uma oferta abrangente de conformidade

Zonas de disponibilidade
•	Fornece proteção contra tempo de inatividade devido a falha do datacenter
•	Separa fisicamente os datacenters dentro da mesma região
•	Cada datacenter é equipado com alimentação, resfriamento e rede independentes
•	Conectadas por meio de redes privadas de fibra óptica

Pares de Regiões
•	No mínimo 300 milhas de separação entre pares de regiões
•	Replicação automática para alguns serviços
•	Recuperação de região priorizada em caso de interrupção
•	As atualizações são distribuídas sequencialmente para minimizar o tempo de inatividade

Regiões soberanas do Azure
•	Serviços Governamentais dos EUA: Atende às necessidades de segurança e conformidade das agências federais, governos estaduais e locais dos EUA e seus provedores de soluções.
•	Azure Governamental: Instância separada do Azure, fisicamente isolada de implantações que não sejam do governo dos EUA, acessível somente a pessoal verificado e autorizado.
•	Azure China: aMicrosoft é o primeiro provedor estrangeiro de serviços de nuvem pública da China, em conformidade com as regulamentações governamentais. Recursos do Azure China: Instância fisicamente separada dos serviços de nuvem do Azure operados pela empresa 21Vianet; Todos os dados permanecem dentro da China para garantir a conformidade.

Recursos do Azure
•	Os recursos do Azure são componentes como armazenamento, máquinas virtuais e redes que estão disponíveis para criar soluções de nuvem.
•	Exemplos: Máquinas virtuais. Contas de armazenamento, Redes virtuais, Serviços de aplicativos, Banco de dados SQL, Funções.
•	Grupos de recursos: é um contêiner que você usa para gerenciar e agregar recursos em uma única unidade. Os recursos podem existir em apenas um grupo de recursos. Os recursos podem existir em diferentes regiões. Os recursos podem ser movidos para diferentes grupos de recursos. Os aplicativos poedm utilizar vários grupos de recursos.

Assinaturas do Azure
•	Uma assinatura do Azure fornece a você acesso autenticado e autorizado às contas Azure.
•	Limite de cobrança: gere relatórios de cobrança e faturas separados para cada assinatura
•	Limite do controle de acesso: gerenciar e controlar o acesso que os usuários podem provisionar com assinaturas específicas

Grupos de gerenciamento
•	Os grupos de gerenciamento podem incluir várias assinaturas do Azure
•	As assinaturas herdam as condições aplicadas ao grupo de gerenciamento

Computação de Rede na Azure

A computação Azure é um serviço sob demanda que forcece recursos de computação, como discos, processadores, memória, rede e sistemas operacionais

Máquinas virtuais do Azure
•	As máquinas virtuais do Azure (VMs) são emulações de software de computadores físicos
•	Inclui processador virtual, memória, armazenamento e rede
•	Oferta de IaaS que oferece personalização e controle total

Conjuntos de dimensionamentode VMs
•	Os conjuntos de dimensionamento oferecem uma oportunidade de balanceamento de carga para dimensionar os recursos automaticamente
Conjunto de disponibilidade de VM
•	Domínio de falha: o rack em si (onde ficam as máquinas)
•	Domínio de atualização

Área de Trabalho Virtual
•	É uma virtualização de área de trabalho e aplicativo executada na nuvem
•	Cria ambiente completo de virtualização da área de trabalho sem precisar executar outros servidores de gateway
•	Reduz o risco de que o recurso seja deixado para trás
•	Implantações reais de várias sessões

Serviços de Contêiners do Azure
•	Os contêineres do Azure fornecem um ambiente leve e virtualizado que não exige o gerenciamento do sistema operacional e pode responder a alterações sob demanda
•	Instâncias de Contêiner do Azure: uma oferta de PaaS que executa um contêiner 
•	Aplicativos de Contêiner do Azure: uma oferta de PaaS, como instâncias de contêineres, que pode balancear a carga e escalar
•	Serviço de Kubernetes do Azure: um serviço de orquestração para contêineres com arquiteturas distribuídas e grandes volumes de contêineres

Azure Functions
•	Uma oferta de PaaS que dá suporte a operações de computação sem servidor
•	Um código baseado em eventos é executado quando chamado, sem exigir uma infraestrutura de servidor durante períodos inativos

Comparar opções de computação do Azure

•	Máquinas virtuais
  •	Servidor baseado em nuvem que dá suporte a ambientes Windows ou Linux
  •	Útil para migrações de lift-and-shift para nuvem
  •	Pacote de sistema operacional completo, incluindo o sistema operacional host
•	Área de Trabalho virtual
  •	Fornece uma experiência de área de trabalho do Windows em nuvem
  •	Aplicativos dedicados para conexão e uso ou acessíveis de qualquer navegador moderno
  •	Permite que vários usuários façam logon no mesmo computador ao mesmo tempo
•	Contêineres
  •	Ambiente leve e em miniatura adequado para a execução de microsserviços
  •	Projetado para escalabilidade e resiliência da orquestração (AKS – Azure Kubernetes Services)
  •	Os aplicativos e serviços são empacotados em um contêiner que fica na parte superior do sistema operacional do host. Vários contêineres podem ficar em um sistema operacional do host

Serviços de Aplicativo do Azure
•	Consistem em uma plataforma totalmente gerenciada para criar, implantar e dimensionar aplicativos Web e APIs rapidamente
•	Trabalha com .NET, .NET Core, Node.js, Java, Python ou php
•	Oferta de PaaS com requisitos de nível corporativo de desempanho, segurança e conformidade

Serviços de Rede do Azure

•	Rede Virtual Azure (VNet) permite que os recursos do Azure se comuniquem uns com os ouros, com a internet e com as redes locais
  •	Pontos de extremidade públicos, acessíveis de qualquer lugar na internet
  •	Pontos de extremidade privados, acessíveis somente de dentro da sua rede
  •	As sub-redes virtuais segmentam sua rede para atender às suas necessidades
  •	O emparelhamento de rede conecta suas redes privadas diretamente
  
•	 Gatway de VPN 
  •	Usado para enviar tráfego criptografado entre uma rede virtual do Azure e uma local pela internet pública
  
•	ExpressRoute
  •	Comunicação direta via cabo
  •	Estende as redes locais para o Azure por meio de uma conexão privada facilitada por um provedor de conectividade
  
DNS do Azure
•	Confiabilidade e desempenho aproveitando uma rede global de servidores de nome DNS usando a rede Anycast
•	A segurança do DNS do Azure baseia-se no gerenciador de recursos do Azure, habilitando o controle de acesso baseado em função e o monitoramento e o registro em log
•	Facilidade de uso para gerenciar seus recursos externos e do Azure com um único serviço DNS
•	As redes virtuais personalizáveis permitem que você use nomes de domínio privados e totalmente personalizados em suas redes virtuais privadas
•	Os registros de alias dão suporte a conjuntos de registro de alias para apontar diretamente para um recurso do Azure





