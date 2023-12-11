# Relatório de Encerramento do Projeto

## 1. Introdução

O presente documento tem como propósito efetuar uma análise comparativa entre o planejamento e a execução durante o desenvolvimento do projeto. Serão avaliados o Backlog, as Histórias de Usuário (US), os Custos, a Qualidade e os Riscos, com o intuito de compreender o avanço do projeto. Adicionalmente, serão conduzidas análises complementares e avaliações para aprimorar a compreensão do estado atual do projeto.

## 2. Backlog

### 2.1  Planejadas

#### Contas

- [[US - 01] - Gerenciar conta](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/100)
- [[US - 02] - Autenticação no PrintGo ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/101)

#### Impressora
- [[US - 03] - Perfil impressora ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/102)
- [[US - 04] - Visualização de dados da impressora ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/103)
- [[US - 05] - Gerenciar dados de contagem da impressora ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/105)
- [[US - 06] - Visualizar impressoras que dados não conferem com dados da locadora ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/106)
- [[US - 07] - Gerenciar chamados técnicos da impressora ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/107)
- [[US - 08] - Visualizar o histórico de localização das impressoras ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/115)
- [[US - 09] - Buscar uma impressora pelo endereço IP  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/116)
- [[US - 10] - Visualizar um relatório  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/118)

#### Manutenção dos equipamentos
- [[US - 11] - Registrar chamados técnicos de impressoras defeituosas por meio do e-mail  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/117)
- [[US - 12] - Receber chamados técnicos de impressoras defeituosas  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/119)
- [[US - 13] - Cadastrar entrega de suprimento  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/120)
- [[US - 14] - Visualizar as entregas de suprimento  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/121)

### 2.2  Realizadas
#### Contas

- [[US - 01] - Gerenciar conta](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/100)
- [[US - 02] - Autenticação no PrintGo ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/101)

#### Impressora
- [[US - 03] - Perfil impressora ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/102)
- [[US - 04] - Visualização de dados da impressora ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/103)

### 2.3 Análise
Foram planejadas 14 atividades no backlog e 4 delas já foram realizadas. Isso significa que 26% das atividades planejadas para o projeto já foram implementadas. Um dos motivos para essa porcentagem foi a necessidade de trabalhar no projeto desde o início, sendo necessária a configuração do ambiente, a realização do deploy do front e de todos microsserviços e a criação das pipelines de CI/CD.

### 3. Qualidade

#### Planejado

Com a finalidade de realizar uma entrega mais segura e confiável para o cliente, a equipe almejou uma cobertura acima de 80% para todos os repositórios. O objetivo era que tanto o Front, quanto os microsserviços apresentassem essa cobertura. Diante disso, os pull requests (PRs) passavam por uma esteira de CI, onde o PR poderia ser mergeado apenas após passar nos requisitos de qualidade definidos: cobertura acima de 80% e não ser responsável por reduzir a cobertura total do código.

#### Executado

Após o desenvolvimento das US, os repositórios apresentaram as seguintes coberturas em suas branches principais:

- **Frontend:** 89,1%
- **PrinterService:** 91,7%
- **UserService:** 93,9%

### 4. Próximos passos

Este documento tem o propósito de fornecer orientações sobre os próximos passos que podem e/ou devem ser executados no projeto, os quais não foram realizados no semestre de 2023/2.


#### Impressora
- [[US - 05] - Gerenciar dados de contagem da impressora ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/105)
- [[US - 06] - Visualizar impressoras que dados não conferem com dados da locadora ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/106)
- [[US - 07] - Gerenciar chamados técnicos da impressora ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/107)
- [[US - 08] - Visualizar o histórico de localização das impressoras ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/115)
- [[US - 09] - Buscar uma impressora pelo endereço IP  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/116)
- [[US - 10] - Visualizar um relatório  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/118)

#### Manutenção dos equipamentos
- [[US - 11] - Registrar chamados técnicos de impressoras defeituosas por meio do e-mail  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/117)
- [[US - 12] - Receber chamados técnicos de impressoras defeituosas  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/119)
- [[US - 13] - Cadastrar entrega de suprimento  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/120)
- [[US - 14] - Visualizar as entregas de suprimento  ](https://github.com/fga-eps-mds/2023.2-PrintGo-Doc/issues/121)

#### Melhorias
- Criar tutorial para deploy de todos os serviços.
- Criar um Swagger para os microsserviços.
- Incrementar docker-compose para executar todos os serviços com apenas um comando.
- Automatizar processo de deploy.
- Melhorar a implementação do docker, de modo que seja possível executar os microsserviços sem que seja necessário rodar `npm i`.

|**Data**|**Descrição**|**Autore(es)**|
|--------|-------------|--------------|
|10/12/2023| Criação do documento | Guilherme Daniel Fernandes da Silva, Vitor Diniz Pagani Vieira Ribeiro, Davi Matheus da Rocha de Oliveira, Antonio Rangel Chaves, Júlia Farias Sousa, Lucas Lima Ferraz, Natanael Fernandes |


