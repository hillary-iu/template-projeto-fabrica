<img src='/img/logo.png' alt='logo da empresa' width='50px' heidth='50px'/>

# *Pet shop e clínica system*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|E-MAIL|
|:---|:---|
|Hillary Eduarda França Amaral Souza|hillary.eduarda@estudante.ifro.edu.br|
|Kemilly Vitória Rodrigues Souza|rodrigues.kemilly@estudante.ifro.edu.br|
|mariany myllena theodoro rasche|myllyna.rasche@estudante.ifro.edu.br|
|Marcela Rocha Dias|m.anna@estudante.ifro.edu.br|
|Anna Victória Reis Marques|annavictoriarmarques13@gmail.com|


# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [REFERÊNCIAS](#referências)

# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | Casa dos Peludos |
| PRINCIPAL OBJETIVO |  O objetivo principal é facilitar a vida do usuário, eliminando a necessidade de utilizar múltiplas plataformas e oferecendo praticidade, economia de tempo e uma experiência simples e unificada no dia a dia. |
| BENEFÍCIOS ESPERADOS |- Aumento de novos clientes e agendamento 24h no site;<br/>- Viabilizar o acesso do cliente á clínica, a loja e ao agendamento de consulta;<br/>- Proporciona ao cliente acesso virtual a informações sobre seu animal como laudos médicos, exames e outros|
| INÍCIO E TÉRMINO PREVISTOS | 01/02/2026 - 07/12/2026 |

[ [INÍCIO](#Pet shop e clínica system) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_Pet Shop System_** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as funcionalidades identificadas durante a fase de concepção do sistema.

[ [INÍCIO](#Pet shop e clínica system) ]

# DESCRIÇÃO GERAL

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário veterinario:**|apenas consulta|
|**Administrador:**|Responsáveis pelo gerenciamento das entidades pertinentes à instituição e pela alocação de outros administradores|
|**vendedor:**|Responsáveis pela aprovação de disciplinas, turmas e matrículas realizadas pela secretaria do curso, além de ser responsável pela alocação da secretaria|

[ [INÍCIO](#Pet shop e clínica system) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 |	Tela Cadastrar Usuário |	Esta tela é responsável por capturar as informações pessoais do novo usuário (tutor). Serve como ponto inicial do cadastro, coletando dados essenciais como nome completo, e-mail, CPF e endereço para criar a conta principal no sistema.|
|RF-002	|Tela Cadastrar Pet	| Acessada imediatamente após o cadastro do usuário, esta tela permite que o tutor cadastre seus animais de estimação. Ela permite informar a quantidade de animais e cadastrar os detalhes de cada um, como nome, espécie, raça, peso e possíveis condições médicas especiais.|
|RF-003 |	Tela Animais Cadastrados|	Exibe uma lista de animais cadastrados no sistema, apresentando as informações do pet e os dados do respectivo tutor informado.|
|RF-004	|Tela Avaliação de Serviço|	Permite que o cliente avalie e comente sobre o serviço prestado durante o agendamento do pet.|
|RF-005	|Tela Relatório de Plano de Assinatura|	Apresenta os planos de assinatura disponíveis para clientes que desejam contratar um pacote completo, incluindo valores e benefícios.|
|RF-006|Tela de Agendamento de Serviço|	Esta tela é destinada ao agendamento de serviços. O usuário pode escolher a data e horário de preferência e confirmar a reserva para os pets previamente cadastrados.|
|RF-07	|Tela Histórico|	Exibe todo o histórico de agendamentos e pedidos realizados pelo cliente, incluindo serviços já concluídos, cancelados ou em andamento.|
|RF-08	|Tela Login|	O aplicativo solicita que o cliente informe seu usuário (e-mail ou nome de cadastro) e senha para confirmar a identidade e conceder acesso ao sistema.|
|RF-09	|Tela Perfil|	Permite que o usuário visualize e edite suas informações pessoais, como nome, e-mail, senha, endereço, foto de perfil e preferências de contato.|
|RF-10	|Tela selecionar serviço|	O usuário pode visualizar e selecionar entre os procedimentos disponíveis (como banho, tosa, hidratação e tratamentos específicos) para o animal escolhido.|
|RF-11	|Tela status de agendamento|	Expõe ao usuário o andamento de seu agendamento (confirmado, Processando ou Recusado).|
|RF-12	|Tela cadastro de serviço|	esta tela aperece apenas para gerente, caso haja a necessidade de adicionar ou excluir algum serviço do catálogo da clínica.|
|RF-13	|Mostar funcionário|	 Este campo aparecerá no histórico de agendamentos do pet para mostrar qual profissional executou o atendimento daquele serviço.|	
|RF-14	|Excluir conta|	Permite que o usuário exclua sua conta do sistema permanentemente.|
|RF-15	|Tela cadastrar funcionário|	apenas o gerente tem acesso e é usada para cadastrar novos funcionários para que o sitema passe a enviar serviços para aquele associado.|
|RF-16	|Selecionar profissional|	Permite que o usuário escolha qual profissional realizará o atendimento apenas em serviços especializados como consultas médicas.|






## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 |Nome do Requisito |Descreva aqui as informações sobre o requisito |
|RNF-002 |Nome do Requisito |Descreva aqui as informações sobre o segundo requisito |
|

[ [INÍCIO](#Pet shop e clínica system) ]

# Prototipagem

[Protótipo criado no FIGMA em 2022 por estudantes](https://www.figma.com/file/iNC7wyX9zP7Kmn3BhiCFGf/Fals6Hood-(Prot%C3%B3tipo-criado-por-estudantes-em-2022)?node-id=0%3A1&t=B16hgeZP3MSURCCa-1)

![Imagem do Protótipo](/img/home.png)

[ [INÍCIO](#Pet shop e clínica system) ]


# Diagrama de Classes

![Diagrama de Classes](/img/diagrama.png)

[ [INÍCIO](#fibonacci-management-system) ]


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
