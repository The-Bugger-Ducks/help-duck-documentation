<span id="topo">

<h1 align="center">Sprint 3: 16/05/2022 a 05/06/2022</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

Na última sprint os esforços da equipe se concentraram na aplicação da análise de causa raíz e em refinamentos de detalhes de interface, permitindo assim que o sistema fosse agradável e intuitivo e, ao mesmo tempo, atendesse aos desejos do usuário da melhor forma imaginada pelo time.

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:
- **RF 04:** Análise de Causa Raíz
- **RF 14:** Avaliação de solução do chamado
- **RNF 08:** Documentação
- **EXTRA:** Relatórios

<span id="entregas">
        
## :heavy_check_mark: Entregas

### RF 04: Análise de Causa Raíz

A análise de causa raíz foi implementada utilizando o esquema de "possíveis soluções para certos tipos de problema", que consiste em categorizar os chamados por tipos de problemas, e, após seu fechamento, seria cadastrado sua solução, assim, chamados com o mesmo tipo de problema terão ao seu dispor essas soluções cadastradas de outros chamados recorrentes, aliviando a carga de retrabalho do suporte, como o demonstrado abaixo:

<div align="center">
    <img src="..." alt="Demonstração da análise de causa raíz">
</div>

Já em questão de auxiliar na redução do retrabalho por parte dos usuários comuns, foi desenvolvido uma área denominada "Centro de Soluções", a qual permite usuários comuns e suportes pesquisarem por uma palavra chave ou expressão e obterem todos os resultados a cerca desta busca, seja por título do problema, título da solução ou descrição da mesma, como o exemplo a seguir:

<div align="center">
    <img src="..." alt="Demonstração do centro de soluções">
</div>

---

### RF 14: Avaliação de solução do chamado

Como um bônus, inspirado em outros sites do ramo de Help Desk e fóruns, foi implementado um mecanismo para avaliação da solução do chamado, sendo contabilizado os votos para "este conteúdo foi útil para mim" ou "este conteúdo não foi útil para mim". Tal ferramenta pode ser observada neste demonstrativo:

<div align="center">
    <img src="..." alt="GIF demonstrativo da avaliação da solução">
</div>

---

### RNF 08: Documentação

Este requisito não funcional do sistema requer a confecção de uma documentação do software, além da disponibilização de um manual de utilização do sistema para os diversos usuários. Tais documentações podem ser acessadas pelos links a seguir:

> **Documentação geral:** ...
> **Manual do usuário:** ...

---

### EXTRA: Relatórios

A partir de toda a coleta de dados realizada pelo sistema (tais como métricas de usuários, em relação a quantidade e cargos, além da quantidade de chamados em cada estágio do ciclo de vida ou quantos problemas semelhantes foram relatados), foi decidido trazer a visualização de algumas dessas estatísticas para o administrador, onde a interface a qual ele acessa para analisar estes dados é a seguinte:

<div align="center">
    <img src="..." alt="GIF demonstrativo dos relatórios">
</div>

---

→ [Voltar ao topo](#topo)

<span id="metricas">

## :chart_with_upwards_trend: Métricas do time

O acompanhamento de atividades, de responsabilidade da Scrum Master, se encontra na imagem adiante, que contém o gráfico Burndown gerado pela equipe (onde o eixo X são os dias trabalhados na sprint e os valores do eixo Y representam as entregas e esforços realizados com o passar do tempo), incluindo as atividades desenvolvidas e seus responsáveis.

<div align="center">
    <img src="..." alt="Gráfico de Burndown da sprint 03">
</div>  
    
<details>
   <summary>Clique aqui para ver as tarefas realizadas na sprint</summary>
   <img src="...">
</details>

→ [Voltar ao topo](#topo)

<span id="links">
    
## :link: Links úteis

- Site do projeto: [https://help-duck.netlify.app/](https://help-duck.netlify.app/), para acessar todas as visões do projeto, utilize os três tipos de perfil, exemplemplificados na tabela a seguir:

|             Usuário comum              |              Usuário suporte              |          Usuário administrador          |
| :------------------------------------: | :---------------------------------------: | :-------------------------------------: |
| email: `user@gmail.com`, senha: `1111` | email: `support@gmail.com`, senha: `2222` | email: `admin@gmail.com`, senha: `3333` |

> **OBS:** Como os serviços em nuvem utilizados para o armazenamento dos respositórios backend são gratuitos, existe o mecanismo de inatividade do serviço, assim, quando acessado pela primeira vez o sistema pode levar algum tempo para acessar seus recursos. Após este primeiro contato, outras requisições são processadas como o de costume.

- Tags foram geradas nos seguintes repositórios para simbolizar o fim da 3ª sprint:
  - Repositório do site: [clique aqui para acessar "help-duck-web"](https://github.com/The-Bugger-Ducks/help-duck-web)
  - Microsserviço de usuários e equipamentos: [clique aqui para acessar "help-duck-register"](https://github.com/The-Bugger-Ducks/help-duck-register)
  - Microsserviço de chamados: [clique aqui para acessar "help-duck-tickets"](https://github.com/The-Bugger-Ducks/help-duck-tickets)
  - Microsserviço de problemas e soluções: [clique aqui para acessar "help-duck-solution-center"](https://github.com/The-Bugger-Ducks/help-duck-solution-center)
  - Microsserviço de relatórios: [clique aqui para acessar "help-duck-dashboard"](https://github.com/The-Bugger-Ducks/help-duck-dashboard)

→ [Voltar ao topo](#topo)
