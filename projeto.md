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
|:---|:---|:---|
|RNF-001 |Tela Cadastrar usuario | Esta tela é responsável por capturar as informações pessoais do novo usuário (tutor). Serve como ponto inicial do cadastro, coletando dados essenciais como nome completo, e-mail, CPF e endereço para criar a conta principal no sistema. |
|RNF-002 |Tela cadastrar pet|Acessada imediatamente após o cadastro do usuário, esta tela permite que o tutor registre seus pets. Ela possibilita informar a quantidade de animais e cadastrar os detalhes de cada um, como nome, espécie, raça, peso e eventuais condições médicas especiais.|
|RNF-003 |Cadatrar serviços|Permite que o gerente cadastre os serviços oferecidos pelo estabelecimento, como banho, tosa e outros, incluindo nome do serviço, descrição, duração estimada e valores praticados.|
|RNF-004 |Animais cadastrados|Exibe a lista de animais cadastrados no sistema, apresentando as informações do pet e os dados do respectivo tutor imformou. |
|RNF-005 |AvaliaçãodeServiço| Permite que o cliente avalie e comente sobre o serviço prestado durante o agendamento do pet.|
|RNF-006 |configuraçoes do cliente| Permite que o cliente edite suas informações pessoais e gerencie seus pets cadastrados (adicionar, editar ou remover).|
|RNF-007 |Relatorio de plano de assinatura| Apresenta os planos de assinatura disponíveis para clientes que desejam contratar um pacote mensal completo, incluindo valores e benefícios.|
|RNF-008 |Relatorio de Vendas| Gera um relatório mensal com o total de vendas realizadas, a quantidade de atendimentos efetuados e outros indicadores para análise do negócio.|
|RNF-009 |Cadatro de agenda se serviço| Esta tela é destinada ao agendamento de serviços. O usuário pode selecionar entre os procedimentos disponíveis (como banho, tosa, hidratação e tratamentos específicos), escolher a data e horário de preferência e confirmar a reserva para os pets previamente cadastrados.|
|RNF-010 |historico|Exibe todo o histórico de agendamentos e pedidos realizados pelo cliente, incluindo serviços já concluídos, cancelados ou em andamento.|
|RNF-011 |login| 	O aplicativo solicita que o cliente informe seu usuário (e-mail ou nome de cadastro) e senha para confirmar a identidade e conceder acesso ao sistema.|
|RNF-012| perfil|Apresenta as informações do usuário, como foto, dados pessoais, endereço, além dos dados dos pets cadastrados.|



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
