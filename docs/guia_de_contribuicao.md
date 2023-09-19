# Guia de contribuição
 
 Este guia tem como objetivo te ajudar a contribuir com o nosso projeto, por favor leia com atenção!

## 1. Antes de começar

Os detalhes de como instalar e executar os projetos podem ser encontrados no [README.md](https://github.com/fga-eps-mds/2023.2-PCGO-DOC#readme).

## 2. Reportando bugs

Você encontrou um bug?

* Sugestões de melhoria são rastreadas através de [_issues_](https://guides.github.com/features/issues/)
e [_pull requests_](https://guides.github.com/activities/hello-world/#pr) no GitHub.
Verifique se nenhuma _issue_ ou _pull request_ foi criada por outra pessoa com o mesmo bug.
* Se não, crie uma _issue_ explicando o problema e adicionando novas informações detalhadas que ajudem
a reproduzi-lo.

## 3. Sugerindo melhorias

Você pode sugerir as melhorias que achar pertinente. Pedimos apenas que tente incluir o
máximo de detalhes possíveis e que verifique se nenhuma _issue_ ou _pull request_ já foi
criado por outra pessoa com a mesma sugestão.

Caso seja algo novo, você tem duas alternativas:

- Criar uma nova _issue_
- Compartilhar a sua sugestão com outros participantes e mantenedores do projeto 

Em ambos, tente usar uma linguagem clara, e com o máximo de detalhes. Qual a motivação,
qual problema resolveria e possíveis desafios, por exemplo, são importantes para entender
o que você precisa. Esse é um projeto de código aberto, mantido por voluntários.
Frequentemente precisamos escolher bem o que vamos fazer com os recursos que temos. :

## 4. Criando _pull requests_

Você decidiu contribuir para o projeto!

Faça um _fork_ do projeto e crie uma nova _branch_.
Mais detalhes [aqui](https://help.github.com/pt/enterprise/2.17/user/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork).

Aqui algumas dicas:

* Caso decida trabalhar em alguma _issue_, comente na _issue_ escolhida. Dessa forma,
outras pessoas saberão que tem alguém trabalhando nela. Caso tenha ficado perdido ou com
dúvidas, peça ajuda.

* Caso tenha visto algo pontual, como um _typo_ ou algo que pode ser corrigido e testado
rapidamente e não envolva mudanças estruturais, você é bem vindo a abrir um novo PR também.

* Antes de qualquer coisa, tente rodar o projeto localmente.

* Rode os testes localmente. Além de ser uma boa prática, previne idas e vindas nas
revisões.

* Adicione novos testes para novas funcionalidades ou bugs.

* Embora o código esteja escrito em inglês, por convenção, as mensagens de _commit_,
comentários, _pull requests_, _issues_, e demais comunicações do projeto deverão ser
escritas em português.

* Marque a opção "Permitir edição pelos mantenedores". Assim poderemos fazer modificações de emergência
mantendo o _pull request_ aberto por você.


## 5. Política de Branch

<p style="text-align: justify; text-indent: 20px">As branches serão nomeadas seguindo de maneira padronizada para a melhorar a organização do projeto. Utilizamos as branchs apenas para desenvolvimento de código sendo que todas as branchs devem ser criadas a partir da <b>main</b> e devem estar nomeadas da seguinte maneira:</p>

``` 
X-NomeDocumento 
Exemplo: 4-CadastroImpressora
```

<p style="text-align: justify; text-indent: 20px"> Sendo que X representa número da issue atribuída seguido pelo nome do documento a ser criado ou modificado, como destacado anteriormente. Em ocasiões em que não se está trabalhando com nenhum documento em específico, então deve-se colocar o nome da issue correspondente.</p>

## 6. Política de Commit

### 6.1 Formato:

<p style="text-align: justify; text-indent: 20px">Os commits devem ser feitos de maneira clara e objetiva respeitando os padrões comentados a seguir:</p>

- Devem possuir um tipo, número da issue associada e o assunto;
- Devem ser escritas em português;
- Os verbos devem estar no gerúndio;

Portanto a formatação do commit será: ` <tipo>(#número da issue): assunto `

#### 6.1.1 Tipos:
- :bulb: quando adicionar nova funcionalidade
- :pencil: quando escrever documentação
- :repeat: quando alguma alteração for feita
- :racehorse: refatoração ou otimização
- :bug: quando consertar um bug
- :fire: quando remover código ou arquivos

<p style="text-align: justify; text-indent: 20px"> Nas ocasiões em que o commit foi realizado por dupla ou grupo, deve ser acrescentado à mensagem do commit o seguinte texto: </p>

```
:bulb:(#04): Desenvolvendo cadastro da impressora

Co-authored-by: Júlia Farias  <julia.farias@gmail.com>
```
## 7. Histórico de versão

|**Data**|**Descrição**|**Autore(es)**|
|--------|-------------|--------------|
|18/09/2023| Criação do documento | Júlia Farias Sousa |
|19/09/2023| Correção gramatical e modificação da política de branch | Júlia Farias Sousa |
|19/09/2023| Revisão do documento | Lucas Lima Ferraz |




