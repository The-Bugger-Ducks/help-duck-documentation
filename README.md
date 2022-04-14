<span id="topo">

<h1 align="center">Sprint 1: 25/03/2022 a 14/04/2022</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

O projeto se baseia no desenvolvimento de um site para Help Desk, que consiste em um sistema com funcionalidades de gerenciamento de usuários, chamados, geração de relatórios, entre outras ações do contexto. Tendo em mente o MVP, a primeira sprint se deu com a criação de um fluxo básico de criação de usuários, login e listagem de chamados, bem como o acompanhamento desses chamados com sua abertura, análise e fechamento. Para isso, foram levantados e validados os requisitos e o protótipo, construindo os serviços e interfaces visando uma entrega de grande valor condizente com a dor do cliente.

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:
- **RF 01:** Registro e acompanhamento de chamados
- **RF 02:** Cadastro e login de usuários
- **RNF 06:** Utilizar Java e TypeScript
- **RNF 07:** Utilizar banco de daos NoSQL

<span id="entregas">
        
## :heavy_check_mark: Entregas
Para entregas da sprint, tivemos os artefatos SCRUM validados, como Backlog do Produto, Backlog das Sprints e User Stories, através de comunicação direta entre o P.O. e o cliente. Para observar esses artefatos, acesse [este link](hhttps://github.com/The-Bugger-Ducks/help-duck-documentation#dart-backlogs--user-stories).

Para extrair e entender os desejos do cliente, foi construído um protótipo inicial no Figma, criando a identidade visual e design do sistema e apresentando para validação com o cliente, onde o resultado deste protótipo, escrito utilizando React e com a integração das funcionalidades acordadas para a primeira sprint pode ser observado a seguir:

<div align="center">

![demo](./demo.gif)
</div>

Este protótipo valida a entrega dos requisitos confirmados para a sprint, onde suas descrições podem ser checadas a seguir:

### RF 01: Registro e acompanhamento de chamados

Este requisito se trata do cadastro e atualizações de chamados, passando por várias fases, como: abertura de chamado, listagem de chamados, observação dos detalhes de um chamado, reverva e atendimento de chamados pelo suport, além de opção para comentários em um chamado, definindo uma discussão em prol da resolução do problema. Este requisito, como o validado, foi desenvolvido na primeira sprint levando em consideração as principais funções para a utilidade geral do projeto, e passará por refinamento e incremento na sprint 2.

### RF 02: Cadastro e login de usuários

Este requisito se trata do cadastro e login de usuários, respeitando a regra de negócio apresentada que permite apenas ao usuário administrados o acesso a funcionalidade de cadastro de novas contas, definindo o cargo destes novos usuários. Já o login, que pode ser acessado por qualquer tipo de usuário, permite a autenticação e autorização do usuário para navegação das telas respeitando seu cargo, por exemplo:

- **usuários do tipo comum** tem em sua página inicial a listagem de todos os chamados que ele próprio já abriu, com a possibilidade de criar um novo chamado ou acessar os detalhes de um chamado da lista, adicionando algum comentário;
- para **usuários do tipo suporte** a tela inicial se configura na listagem de chamados abertos por qualquer usuário e ao acessar os detalhes de um chamado é pssível reservá-lo, adicionar algum comentário ou marcá-lo como concluído;
- já para **usuários do tipo administrador** tem a apresentação da listagem de todos os usuários em sua página inicial, com a opção de cadastrar novos usuários.

→ [Voltar ao topo](#topo)

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Em prol de um melhor aproveitamento das habilidades de cada integrante, o time foi separado em duas frentes: frontend e backend, onde, na primeira sprint, o time de frontend ficou responsável pela confecção do protótipo, projeto frontend e integração de funcionalidades enquanto o time de backend ficou responsável pela criação dos microsserviços necessários e pesquisas sobre o tema do desafio. 
- O acompanhamento de atividades, de responsabilidade da Scrum Master, se encontra na imagem adiante, que contém o gráfico Burndown gerado pela equipe (onde o eixo X são os dias trabalhados na sprint e os valores do eixo Y representam as entregas e esforços realizados com o passar do tempo), incluindo as atividades desenvolvidas e seus responsáveis.
    
<div align="center">
    
![Burndown Chart](https://user-images.githubusercontent.com/69374340/163472803-4912e725-f05c-4cdc-84bc-29ae2953f401.png)
</div>
    
<span id="links">
    
## :link: Links úteis

- Site do projeto: [https://help-duck.netlify.app/](https://help-duck.netlify.app/) (usuário exemplo - email: `user@gmail.com`, senha: `1357`)
- Tags geradas em cada repositório que simbolizam o fim da 1ª sprint:
  - Repositório do site: [clique aqui para acessar "help-duck-web"](https://github.com/The-Bugger-Ducks/help-duck-web)
  - Microsserviço de autenticação: [clique aqui para acessar "help-duck-authentication"](https://github.com/The-Bugger-Ducks/help-duck-authentication)
  - Microsserviço de usuários: [clique aqui para acessar "help-duck-users-microservice"](https://github.com/The-Bugger-Ducks/help-duck-users-microservice)
  - Microsserviço de chamados: [clique aqui para acessar "help-duck-requests"](https://github.com/The-Bugger-Ducks/help-duck-requests)

→ [Voltar ao topo](#topo)
