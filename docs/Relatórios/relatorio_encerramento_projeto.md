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

### 3. Custos Executados
Autor e dono do documento: [Lucas](https://github.com/mibasFerraz)
<iframe width=100% height=500px src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRJ0NLYnJswEZw9qclqGsOHgU65ek88FSZPq6ADx4ZFnajxMngSR8-Kx9UrdiBgQA/pubhtml?widget=true&amp;headers=false"></iframe>


### 4. Riscos
Durante o decorrer do projeto, o time enfrentou diversas dificuldades principalmente envolvendo os riscos que tratam sobre comunicação, tanto entre os membros do time, tanto com os clientes, conflito de horários, conflito entre atividades de outras matérias e da baixa produtividade do time durante boa parte do projeto. Esses riscos principais são retratados na planilha como R5, R6, R10, R12, R13.<br>
A ocorrência desses riscos a partir da primeira semana de desenvolvimento afetou significativamente o trabalho do time e geraram ao decorrer do projeto um agravamento dos riscos R1 (principalmente entre os membros de MDS), R2 e R9. Culminando em tarefas feitas pela metade e no atraso consecutivo das entregas das releases.<br>
Antes do começo do desenvolvimento, o time realizou treinamentos das tecnologias básicas do projeto com os membros de MDS, porém por conta dos problemas enfrentados durante o projeto e também por uma certa falta de comprometimento, o aprendizado de boa parte dos membros assim como suas participações no projeto foram muito limitadas.<br>
O time só foi capaz de lidar de certa forma com os problemas na parte final do projeto, com duas semanas da entrega final. Foram desenvolvidas 2 releases que não foram totalmente validadas pelos clientes, justamente por conta da limitação de tempo para realizar correções.<br>
A planilha de riscos só foi documentada e analisada até a segunda sprint.


<iframe width=100% height=500px src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTAV-yFXWIarhSAXJnwa1TGx-ySa_kf8feAIaN1JP4DSO0eZqDzA4zquzTCbaYnXBnHJVmSdOqw_fAR/pubhtml?widget=true&amp;headers=false"></iframe>


### 5. Qualidade

#### Planejado

Com a finalidade de realizar uma entrega mais segura e confiável para o cliente, a equipe almejou uma cobertura acima de 80% para todos os repositórios. O objetivo era que tanto o Front, quanto os microsserviços apresentassem essa cobertura. Diante disso, os pull requests (PRs) passavam por uma esteira de CI, onde o PR poderia ser mergeado apenas após passar nos requisitos de qualidade definidos: cobertura acima de 80% e não ser responsável por reduzir a cobertura total do código.

#### Executado

Após o desenvolvimento das US, os repositórios apresentaram as seguintes coberturas em suas branches principais:

- **Frontend:** 89,1%
- **PrinterService:** 91,7%
- **UserService:** 93,9%

### 6. Próximos passos

- Verificar com os clientes quais critérios de aceitação não foram aceitos, para que as histórias de usuário 01, 02, 03, 04 possam ser consideradas entregues de fato.
- Fazer protótipos de alta fidelidade da US09 até a US13
- Implementar US05 até US13
- Fazer a análise de riscos de cada sprint realizada
- Realizar e documentar testes funcionais



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
- Automatizar processo de deploy nos microsserviços.
- Melhorar a implementação do docker, de modo que seja possível executar os microsserviços sem que seja necessário rodar `npm i`.
- Alterar a arquitetura, de forma que cada microsserviço tenha um banco de dados.
- Refazer plano de custos, para levar em consideração a inflação de 2019 até a data presente
- Utilizar mais componentes do React no frontend.
- Atualizar as issues das histórias de usuários com os prints dos protótipos que estão faltando
- Fazer manual de instalação do projeto para que o cliente Vidal possa implantar o sistema nas suas máquinas virtuais na Polícia Civil. Ou então marcar uma reunião com o mesmo para que essa instalação possa ser feita com ajuda do time. 
- Atualizar critérios de aceitação das US01, US03 e US04 para que conste o consumo do Schedular. E na US01 precisa constar o critério da listagem de usuários
- A US15 deve ser uma tarefa da US01
- Ao atualizar algo no backend, é necessário atualizar o banco de dados e o pacote @fernandes-natanael/printgo-prisma manualmente em cada microsserviço. Seria interessante que isso fosse automatizado.



|**Data**|**Descrição**|**Autore(es)**|
|--------|-------------|--------------|
|10/12/2023| Criação do documento | Guilherme Daniel Fernandes da Silva, Vitor Diniz Pagani Vieira Ribeiro, Davi Matheus da Rocha de Oliveira, Antonio Rangel Chaves, Júlia Farias Sousa, Lucas Lima Ferraz, Natanael Fernandes |
| 16/12/2023 | Finalizando documento | Antonio Rangel e Felipe Amorim |


