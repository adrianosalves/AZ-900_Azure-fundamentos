# AZ-900_Azure-fundamentos
AZ-900_Azure-fundamentos
AI_900 - 
DP_900 - 

Codigo 900 - Nivel basico naquela ferramenta.



Curso inicial para abiente em cloud marco 0 para ter uma base inicial para solução Microsoft!

Preparação para Certificação!

Cerificação atestado que voce tem um dominio sobre um determinado assunto e te uma chance maior para conseguir uma vaga de emprego.

Material Oficial é o Learning

Estudar e fazer o Laboratorio o apoio.

Não podemos fazer a disponiblização dos slide das aulas!

8 Semanas de curso termino por volta de junho...

Prova será no idioma em porugues...

Sera disponibilizado durante o ano todo esses cursos.

Vamos criar conta de aluno no AZURE e usar por 12 meses sem custo.

# Inicio do Curso Oficial AZ-900

Grupo WhatsApp
Conta do Learning (Use contas vinculadas a Microsoft)
Prova pode varia entre 35 a 45 perguntas, pode ser com mais de uma alternativas corretas podendo var ate meio ponto.
Questionario no Learning pode fazer quantas vezes quisers não é eliminatior e conta pontos.
Salve seu link inicial
Estudar o Learning durante a semana...
E fazer a perguntas do conteudo estudado!
Teremos simulado durante o curso!
So tera 100 voucher disponibilizado pela Microsot.
Apos receber voucher fazer a prova o mais breve possivel no maximo 15 dias
Certificado (Apos conclusão do Curso) x Certificação (Da Microsoft apos passar do Exame)

Certificações:

Linha AZ-900 - Básica
Linha AZ-104 - Intermediaria
Linhha AZ-303,304,400 - Avancada

On-Primise - Modelo Antigo Comprar servidor

Torelancia a falhas : São falhas tecnicas não recuperacao de desastres.

Comparar CapEx: Comprar para mim investimento alto.

Despesas Operacionais (Opex): Nuvem é comprar sobre demanda conforme em uso.

# Modelo baseado em consumo

Provedores de serviço de nuvem so paga o que consome.

. Melhora previsão dados
. São forneciso precos especifico e idividual.
. Cobranca e baseada no uso real.

# IaaS: 

Criar uma Infraestrutura de TI Servidores, VPC, rede. O cliente pode gerenciar o sistema operacional ao seu modo: Atualizar, Backup e etc....

# Paas (Plataforma como Serviço)

Oferece um ambiente que voce crie, teste e implanta com aplicativos de software sem foca no gerenciamento de infraestrutura subjacente. A Microsoft se encarrega de manter o sistema atualizado. Ex: Servico de Banco de Dados.

# SaaS (Software como Serviços)

Os usuario se conectam e usam aplicativos com base em nuve pela internet por exemplo, Microsoft Office 365, email e calendarios.

# Modelos de Nuvem

Iaas: 
.Serviço de nuvem mias flexiveis
.Voce confgura  gerencia o hardware para seu aplicativo

PaaS
.Foco no desenvolvimento de aplicativos
. Ogerenciamento da plataforma é manipulado pelo provedor de nuvem.

SaaS
.Modelo de preco de pahgamento confrme o uso
.Usuario pagam ple software que usam em um modelo de assintura.

Modelo de responsabilidade:

Ex:

Iaas: Carro na locadora (Localiza): Entregar com o tanque cheio e etc...
Paas: Uber vice direciona...
Saas: Onibus rota tracada.


# Computacao sem servidor - Server less

Azure functions: codigo é executadas exemplo para autopreencimento.

Aplicativo logico do Azure: Automatizar tarefas fluxo de trabalho sistemas e serviços.

Grade de Eventos: Compilar aplicativos com base em eventos, gerenciar e controlar todos os eventos.

Analise mais detalhes as categorias mais usadas:

1.Computacao
2.Rede
3.Armazenamento
4.Movel54.Banco
5.Web
6.Iot
7.Big Data
8.IA
9. DevOps

Hierarquia

1.Management Groups
2.Subscriptios
3.Resources Groups
4.Resoureces

# Modulo 2: Princípios básicos do Microsoft Azure: descrever os principais serviços do Azure

https://docs.microsoft.com/pt-br/learn/paths/az-900-describe-core-azure-services/

Quiz; Simulação de aprendizado. (https://quizizz.com/join/game)

O que um é uma região: POsso alcar recursos compostas de DataCenters.

Exemplo: Brazil é uma regao compostas de um ou mias DataCenters.

Busque uma região que tenha uma baixa latencia proximo do seu Pais e leve em consideração o Custo disso.

Atualmente existe mais de 60 regioes dentro do Azure em ais de 140 paises.

OBS: LGPD algumas leis exige que as informações esteja armazenado naquela região de acordo com a LGPD.

Os DataCenters são replicadas para outras regiões espalhada no mundo (Para outras cidades ou Paises).

# Pares de Regiões

No minimo 300 milhares de serapacao entre pares de regioes.

https://aka.ms/PairedRegions-ptb

# Zonas de disponilidade

. O que é? Conjunto de DataCenters ex: 3 ou mais...
. O DataCentre não tem como escolher. Escolhesmos a Região.
. Podemos escolher a zona de disponibilidade > SLA (Disponibilidade de serviço %99,9).
. Zona de Disponibilidade não tem SLA ...

Em que momento devemos escolher a zona de disponibilidade?
Vai depender do estado critico da aplicação?
Como podemos medir isso dentro do Azure?

Zona de Disponibilidade: Proteção contra falha (Falha Fisica no DataCenter- alagamento e etc....!

Por que o Recuperacao de Desastre não tem SLA? ..Por que o tempo pode ser variavel de acordo com o ambiente.

Zona de Disponibilidade dentro dessa região.

Um recurso precisa estar alocado a um grupo de recurso. (Exe: Uma pasta):
. Um recurso é unico.

É parecido a um Container.

Grupos de recursos:

. Os aplicativos podem utilizar varios grupo s de recursos.

. Grupo de Recusos: Facilita a organização pelo tipo, pelo uso e localização, administração bem organizada facila Administração e Gerenciamentos.

. Grupo de Recursos dentro de Outro não pode existir não são aninhados...

.Assinatura Financeiro
.Assinatura MKT
.Assinatura RH

# Azure Resoure Manager

. Faz um API o meio de campo para permitir ou negar determinado serviço, crie atualize ou remova determinado recurso.

.Portal do Azure, PowuerShell, CLI, Clientes REST ---> SDKs ---> Azure Resource Manager <-->
. Banco de Dados, App Web, VPC, Gerencias Servicos, Outros....

# Principais Caras de Trabalho no Azure - Dominio de Objetivo

Descrever os beneficios e o uso de:

Servcos de computação do Azure

Computacao do Azure é um serviço de computacao sob demanda que forbece recursos de computacao, como discos, processadores, memoria, rede e sitemas operacionais.

1. Maquinas virtuais do Azure (VM): S]ao emuadores de software de computadores fisicos.

. Inclui processador virtual, memoria, armazenamento e rede.

. Ofertas de IasS que oferece personalizacao e controle total.

Orientacao de como criar uma maquina virtual (De exemplos).

# Serviços de Aplicativos do Azure

Serviços de aplicativos é uma plataforma totalmente gerenciada para criar , implantar e escalar aplicativos web e APIs com rapidez.

Oferta de PaaS com requistos de nivel corporativo de desempeho, segurança e conformidade.

Trabalha com NET.NET Core, Node.js, Java, Python e outras.

#  Serviços de Conteiner do Azure

Instancias de Conteiner do Azure: Uma Oferta do PaaS que executa um containe no Azure sem precisar gerenciar uma maquina virtual ou serviços adicionais.

Serviços de Kubernets do Azure: Um serviço de orquestacao para conteiners com arquitetura e grandes volumes de conteineres.

# Area de Trabalho Virtual do Azure

É um especie de viirtualização do Desktop na nuvem.

. Criar um ambiente completo de virtualizacao da area de trabalho sem precisar executar outros servidores de gateway.

. Publicar pools de host ilimitados para acomodar várias cargas de trabalho.

. Reduzir custos com recursos em pool, com várias sessoes.

# Serviços de rede do Azure

A rede virual (VNet) do Azure permite que recursos do azure se comuniqye entre si e com a rede locais.

O #Peerin# permite a integracao de varias redes virtuais conectadas por meio do Azure.

#  Serviços de rede do Azure

O Gateway de Rede Virtual Privada (VPN) é usada para enviar trafego criptografado entre uma rede virtual do Azure e uma rede local na internet. Um tunel de acordo com todas as normas de segurança. Trafego entre pontos de rede camada 'Autenticacao'.

Ex:

VNet <---> VPN Gatewaye (VPN) <---> IPSec IKE S2S VPN <---> On-premises LocalSite 1 (VPN)

# Serviços de Rede do Azure

O Express Roue do Azure permite a conexao da minha rede privada a rede do Azure.

- Camada 2 (L2): Essa camada de vinculo de Dados, que fornece comunicacao de nó entre ddois nós na mesma rede.


- Camada 3 (L3): ... endereço e roteamento entre nós em uma rede de varios nós.

# Azure networks servces.

. Azure Load Balancer: Faz o escalonamento automatco para criar um acesso de alta disponibilidade para acessar aplicações ou recursos.

. Content Delivery Network (CDN): é uma rede distribuida, colocando uma copia dos arquivos em todos os servidores, e na hora que voce vai fazer um download desse arquivos possa ser encontrado em um servidor mais proximo e diminua a latencia.

. Azure Application Gateway: é um balanceador de carga do trafego da Web qe permite que voce gerencie o trafego para seu aplicativo Web. Trafego entre aplicações, camada OSI 7 de aplicação.

# Tipos de Armazenamento Dados:

.Estrturados: 

.Semi-estrturados:

.Desinstruturados: Não possue estrutura de dados definida, BLOBs (Binary Large Objects).

# Armazenamento

.IaaS: Discos, Aruqivos

.PaaS: Containesr, Tabelas, Queues(Filas)

# Serviços de Armazenamento do Azure

.O Armazenamento de conteiner (blob) é otimizado para armazenar grandes quantidade de dados não estruturados, como dados binarios ou de texto.

.O armazenamento de disco fornece disicos para maquinas virtuais aplicativos e outros serviços acessarem e usarem.

.Os arquivos d zure configuram compartilhamento de arquivos de rede altamente (SMB). Armazenamento compartilhado entre VM e conteiners.

# Camadas de acesso de armazenamento do Azure

Host: 

Cool:

Archive:

# Serviços de Bacno de Dados do Azure (Paas):

. Azure Cosmmos Database é um banco de dados relacional como serviço de banco distribuidoalmente que escala de maneira elatica e independente taxa 99.999% globalmente.


SQL do Azure


MySQL

PostgreSQL


Azure DatabSe Migration Service.


# Instancia Gerenciada de SQl do Azure

Permite que os clientes do SQL facam a migracao do SQL para a Nuvem.

# Explorar o Azure MarketPlace:

É uma loja que permite voce localizar experimentas e comprar os aplicatios e serviços de centenas dos principais provedrdores de serviços certificados  para execução.


# Modulo 3 - IoT Internet das Coisas

O que é IoT: São aparelhos que conseguimos comunicar com a Internet exemplo hoje existe aparelhos de Ar Condicionado que voce consegue acessar antes de voce chegar na sua resisidencia seu apapareho pode sr programado para ele ligar antes de 15 min para quando voce cehgar o ambiente esteja na temperatura ideial. 

Azure ioT Cenral: é uma expecie de console onde centralizado todas as questoes de generenciamento da Internet das coisas, essa interface é bem visual e faciltta conectar, monitora e gerenciar ativos de IoT em escala.

O hub IoT do Azure: é um serviço gerenciado hospedado na nuvem que atua como um hub central de mensagens para comunicoacao bidirecional entre os aplicativos ede IoT e dos dispositivos que ele gerencia.

O Azure Shpere ´e uma plataforma de aplicativ segura e de alto nvel com recusos intrenos de cmo comunicao e seguranca para dispositivos cnectados a internet.

Azure IoT Edge: é um servio totalmente gerenciado desenvolvido om base no hub IoT do Azure. Impmate suas cargas de Trbalaho de nuvem - serviços de intelegencia artificail do Auzre e de terceieros ou sua propria logica de negocios - para serem exeuctaddas em dispositivos Ipor o pde dados or meio de conteieres..

# Big data e analise: Grande variedades de volume em constante mudanças.

Variedade, Volume e Velocida.

fonte adicional

Asure Synapse Analytice: analise ilimitada, data warehouse empresarial

Azure HDInsight: Apache Hadoop

Azure Databricks: Apache Spark

Azure Data Analytics: transformação paralela

# IAe Machine Learning

Azure Machine Learning: baseado em nuvem para desenvolver , treinar e implantar modelos de machine learning.

Serviços Cognitivos: habilidade  rapidamente os aplicativos para ver, ouvir, falar, entender e interpretar as necessidades de um usuarios.

Serviço de Bo do Azure: desenvolver bots inteligentes de nivel empresarial.

OBS:  que é Bot? É um robo que automatiza tarefas um agente virtual. Exemplo: Claro, Whatsapp atendimento virtual. Ele inicia uma conversação com base em respostas de frma intelifencias com a IA.

# Tipos de Serviços cognitivios IA:

Language, Speech (Converte fala em texto), Vision, Decision

A capacidade de buscar infromacoes e obter resultados muito satisfatorio.

# Computação sem Servidor

.Azure Functions: Buscar informacoes e obter resultas Codigo baseado em evento executando o serviço e não a infraestrturua subjacente. Linguagem de prograacao de sua preferenceia.

.Aplicativos Lógico do Azure: automatizar e orquestrar tarefas e integracao com outros aplicativos.

# Desenvolver aplicativos com DevOps e GitHub (Certificação AZ-400)

Azure DevOps: ferramentas de colaboradores de desenvolvimento, inluindo pipelines, cartoes Kaban e teste de carga automatizados baseados em nuvem.

Github: hosting de desenvolvimento de software com controle de versão, gerenciamento de código-fonte e gerenciamento de bugs/tarefas.

GitHub Actions para Azure: automatizar o fluxo de trabalho de software para criar , testar e implantar de dentr do GitHub.

Azure DevTest Labs: criar rapidamente ambientes no Azure enquanto minimiza os gastos e controla os custos.

# Ferramentas de Gerenciamento no Azure (ARM):

Portal do Azure: Painel via Web

Azure PowerSell: Linux, Windows  Ma

APlicativo Movel do Azure: Android e IOS, coisas mais simples iniciar e parar uma VM, mas para gerenciar é muito pequeno.

Interface de Linha de Comando (CLI): Baixar o instalador para seu computador semelhante ao powershell, porem os comandos é mais voltado para o Linux. Pode ser instalado WIndows, Linux e MAC.

API REST do Azure: Permitir Gerenciar e Excluir recursos... ão APIS para obter possibilidade de explorar mais recursos.

Azure Cloud Shell: É uma console por linha de commando pela pagina Web.

# Azure Advisor

É uma ferramenta para informar o que precisa ser melhorado dentro da plataforma. Ele faz recomendações com base nas melhores práticas para otimizar as implatações do Azure. Também acessível por API e voce pode configurar otificações com base nas melhores práicas pra otimizar as implantações.



# Azure Monitor

É uma afrerrameta pra monitorar a situação do seu ambiente não faz recomendações faz o gerenciamento da saúde do seu servidor ( Memoriar, CPU espaçõ em disco) atraves do painel personalizaveis. Monitora e toma ações de acordo com as metricas e politiia definida pelo Administrador do ambiente.

Application Inights: Metricas e Logs de Aplicações com rastreamento e mapeamento fima-fim
Log Analytics:
Alerts:
Automation Buscas: 

# Integridade do Serviço do Azure / Azure Service Health

Avaliar o implacto de problemas de serviços do Azure com atualizações personalizadas de orientacoes , suporte, ntiticações e resolução de problemas. Personalizar relatorio para enviar para seu cliente sobre uma determinar Maquina Virtual.

Ele é mais focado em manuteções planejadas se aplica em ponto de atenção fora do ambinete de alta disponibilidade que não impacta no ambiente de alta disposniblidade.

# Modelos do Azure Resource Manager (ARM)

São arquivos JavaScript Object Notation (JSON) que pode ser usados para criar e implantar a infraesrutura do Azure sem precisar gravar comandos de proramacao.

. Sintaxe declarativa
. Resultados repoduziveis
. Orquestração
. Arquivos modulares
. Validação integrada
. Codigo exportavel

OBS: É possivel importar maquina via arquivos (JSON) e deixar as maquinas ativas de foma muito mais rapida.

# Treinamento de Resumo Modulos 1,2,3 e depois um simulado para medir um conteudo absorvido do Microsoft Learn:

Resumo:

# O que é computação em nume?

É a entrega de serviços de computação por meio da internet, possibilitando um inovação mais rapida, recursos flexiveis e economia de escala.

COimputacao, rede armazenade, ...

# Nuvem pública

. Pertence a serviços de nuvem ou Provedor de hosting

. Fornecer recursos e serviços a varias origaniacçoes e usuarios

. Acessados via conexao de rede seguran (Geralmente pela internet)

** DICA: Sabemos a região, mas não o datacenter em que esta alocado. **

# Nuvem privada

. As organnizações criam um ambiente em nuvem em seu datacenter.

. É responsavel por operar os serviços que fornece

. Não fornece acesso aos usarios fora da organização.

# Nuvem hibrida

. Combina as nuvens Publica e Privada para permitir que os aplicativos sejam executadas no local mais apropriado.

Ex: Aplicativos em nuvem Pública e o Banco de dados local.

Muito utlizado atualmente pode ser o mas seguro vai depender da situação. Cada caso precisa ser analisado.

# Comparativos do modelo nuvem

Publica : 
. Nunhuma despesas de capital para escalar veriticalmente

Privada:
. O hardware dee ser adquirido para inicial manutenca

Hubrida:
. Oferece a maior flexibilidade

** Consultar imagem **

# Beneicios da Nuvem

Alta disponibilidade: Obter o recurso de quando eu preciso, essa semana em apenas alguns cliques, exe: aumentar um HD.

Tolerancia a falhas: Replicacao de informação (Entreve VMs) mesmo que acontece um problema no HD, Fonte Queimada, meu serviços continuar funcionando. É diferente de Desastre Recovery.

Escalabilidade: Mudanca de recursos ex: Memoria, HD e etc... Pode ser vertifical (Hardware) e Horizontal (Maquina Virtual no limite e desejo criar uma outra para dividir a carga de trabalhar entreas as maquinas).

Elasticidade: Aumento de recurso para atender a minha necessidade Ex: Black Friday, . Eslasticidade permite fazer a escalabilidade.

Alcance global: Todo provedor de serviço tem Datacenter espalhado nos 4 cantos do mundo.

Capacidade de Latencia: Possibilia um tempo de resposta muito baixo, permitindo uma resposta mais rapida.

Agilidade: Escluir um recurso rapidamente.

Consideracao sobre custo preditivo: Estimativa de custos, não preciso, mas te dar um previsão atraves de uma calculadora.

Recuperacao de Desastres: Tenho um problema preciso subir o serviço em outra região sai do Brasil e vou para EUA. Não tem SLA para essa situação.

Segurança: Nivel de segurança é mais elevado mais que um servidor interno, a Microsoft investe e disponibiliza recursos para manter seus servços segurança.

OBS: 

# Comparar CapEx e OpEx

. CapEx: OnPrimise gastos com infrastrutura gasto inicial de dinhiero

. OpEx: Compra sobre demanda paga depois de 30 dias depois será pago.

# Modelo baseado em consumo

. Melhor previsao de custos

# Serviços de Nuvem - Dominio de Objetivo

As responsabilidades vão aumentando...

. IaaS: 
. Suporte Local maior responsaverl
. Armazenamento, Rede e Sistemas Operacional
. O Cliente escolhe o Sistema Operaciona e realiza toda a manuteção...
. Serviço mais flexivel configura e gerencia o Hadrware para o aplicativo

. PaaS:
. Não me preocupo com a Infraestrutura
. Muito ultizado em Banco de Dados
. Gerenciamento da plataforma e feito pelo Provedor da Nuvem

. SaaS: 
. Provedor é responsavel pela manuntenção...
. Utiliado com serviços Teams, Google Drive, Office 365.
. Pago em modelo de Assinatura


# Computação sem Servidor

. Azure Functions: Consultar pequenas tarefas

. Aplicativos Logicos do Azure: Automatizar tarefas...

. Grade de Eventos: Monitoramento do dois acima...

# Contas do Azure

Para acessar o Azure é necessário a criação de uma conta que será sempre gratuita (Acessar ao Azure):

A assinatura será paga de acordo com os recursos que forem usado.

Podemos ter varias assinaturas dentro de uma conta.

Limite de controle de acesso.

@cocacola.com.br
. Assinatura pode criada; com perfil diferente; (Granular com detalhes de acordo com a necessidade);

# Modulo 2:

# Regiões

. Uma região pode permitir uma baixa latencias, quanto mais proximo maior o custo, e pode ser que seja necessário de acordo com a LGPD.

. Permite escolher um custo de acordo com o bolso atraves de uma calculadora de custo.

. Toda região tem um par e replica as informações para outra região, caso tenha um desater recovey ele sera acionado e ativa os serviços em outra região.

# Zona de Disponibilidade (Datacenters espalhados)

Região --> Zona 1 (datacenters), Zona 2 (datacenters), Zona 3 (datacenters)
. Protege contra falhas de inatividade.

Datacentre sempre será retrito a mesma região? ou ele pode ter uma maior abrangencia de região?

# Recursos do Azure

Maquinas Vitruais, Contas de Armazenamento, Redes Virtuais, Serviso Web, Bacnos de Dados, Funções

# Grupo de Recursos

. É igual uma pasta que armazena (recursos do azure)
. Os recurso so pode estar em um grupo de recursos
. O recursos pode existir em diferentes regiões.
. Os recursos pode ser movido para diferentes grupo de recursos.
. Os aplicativos pode utilizar varios grupo de recursos.

# Azure Resource Manager

. É camada do Azure que permite o gerenciamento de criacao ou exclusão de um determinado recursos (Portal Azure, CLI, PowerShell, Cliente REST).



























































