<span id="topo">

<h1 align="center">Sprint 2: 25/04/2022 a 15/05/2022</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

Nesta segunda sprint a equipe se voltou a atender os requisitos previstos para a sprint, além de levar em consideração os desejos apontados pelo cliente durante a apresentação do pitch, onde foram implementadas ordenação de vários contextos (como chamados, usuários e equipamentos), além de iniciar a aplicação de análise de causa raíz na abertura de chamados e relacionar equipamentos aos mesmos, entre outras funcionalidades como a edição e exclusão de usuários, identificação da solução e do responsável pelo fechamento de cada chamado, bem como acesso dos chamados fechados por todos os usuários e o refinamento da responsividade em todas as telas do sistema.

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:
- **RF 01:** Registro e acompanhamento de chamados
- **RF 02:** Gerenciamento e login de usuários
- **RF 04:** Análise de causa raíz
- **RF 11:** Gerenciamento de equipamentos
- **RNF 09:** Sistema responsivo

<span id="entregas">
        
## :heavy_check_mark: Entregas

### RF 01: Registro e acompanhamento de chamados
<details>
   <summary>Clique aqui para ver detalhes sobre o desenvolvimento deste requisito</summary>
    <br>
   Tal requisito foi iniciado na sprint 01, tendo previsão para fechamento nesta sprint, como o ocorrido. Dentre as funcionalidades que já haviam sido desenvolvidas estavam, por parte dos usuários comuns: cadastro e listagem de chamados, além de possibilidade de adicionar comentários; e por parte dos usuários suportes: listagem de chamados, permitindo a reserva e fechamento de chamados. O refinado durante esta sprint foram a aplicação de ordenação de chamados, bem como sua solução e identficação do usuário suporte responsável pelo fechamento do chamado, além de permitir que usuários comuns acessem e observem o decorrer da resolução de chamados previamente fechados criados por outros usuários.

<div align="center">
<img src="https://user-images.githubusercontent.com/69374340/168503190-a3660ad5-f46b-47f0-b01d-97499f9de4e9.gif" alt="GIF demonstrativo do registro e acompanhamento de chamados">
</div>
</details>

---
    
### RF 02: Gerenciamento e login de usuários
<details>
   <summary>Clique aqui para ver detalhes sobre o desenvolvimento deste requisito</summary>
    <br>
    Iniciado na primeira sprint com o cadastro, listagem e login de usuários, foi incrementado nesta sprint com as opções de edição de perfil e exclusão de usuários (este último, por conta das regras de negócio levantadas, apenas permitido à usuários administradores do sistema).

<div align="center">
<img src="https://user-images.githubusercontent.com/69374340/168503226-62bb3d32-4e11-4a6d-9a6b-621b1d4448cd.gif" alt="GIF demonstrativo do gerenciamento e login de usuários">
</div>
</details>

---
    
### RF 04: Análise de causa raíz
<details>
   <summary>Clique aqui para ver detalhes sobre o desenvolvimento deste requisito</summary>
    <br>
    Requisito funcional avaliado pelo cliente como um dos mecanismos de mais valor no projeto, o qual se dá por uma saída à dor do cliente de retrabalhos desnecessários. Tal assunto requeriu muita pesquisa e esforço do time para entendimento e elaborações de possíveis fluxos e integrações com o projeto, onde, validando com o cliente, foi decidido uma ideia base:
<br><br>
    
> a análise de causa raíz seria implementada utilizando o esquema "tipos de problema, tipos de solução" que consiste em categorizar os chamados por tipo de problema, que seriam a causa comum de 1 ou mais chamados, e, após seu fechamento, categorizaria-se a solução, dessa forma, qualquer chamado que fosse criado a partir de um "tipo de problema" teria a seu dispor "tipos de soluções" recorrentes, aliviando a carga de retrabalho.
    
</details>
    
---
    
### RF 11: Gerenciamento de equipamentos
<details>
   <summary>Clique aqui para ver detalhes sobre o desenvolvimento deste requisito</summary>
    <br>
    Tal funcionalidade foi requerida pelo cliente afim de cadastrar e acompanhar o estado de seus equipamentos, desta forma foram criados formulários de cadastro e edição de equipamentos, bem como a sua listagem, a qual só pode ser acessada por usuários administradores. Sua relação com a abertura de chamados ainda está sendo estudada e validada para seguir a melhor abordagem para as dores do cliente.

<div align="center">
<img src="https://user-images.githubusercontent.com/69374340/168503264-00cebafd-d373-4f23-99d4-d21795aff6a4.gif" alt="GIF demonstrativo do gerenciamento de equipamentos">
</div>
</details>
    
---
    
### RNF 09: Sistema responsivo
<details>
   <summary>Clique aqui para ver detalhes sobre o desenvolvimento deste requisito</summary>
    <br>
    Dado requisito não funcional do sistema condiz com a necessidade de responsividade do projeto, para que se adaptasse a diversos tipos de dispositivos, tais como notebooks, tablets, celulares ou mesmo televisões, e assim foi entregue nesta sprint: todas as telas já desenvolvidas receberam uma atualização para garantir a responsividade entre os tamanhos de tela.
    
<div align="center">
<img src="./responsividade.gif" alt="GIF demonstrativo da responsividade apresentada pelo sistema">
</div>  
</details>
    
---

→ [Voltar ao topo](#topo)

<span id="metricas">

## :chart_with_upwards_trend: Métricas do time

O acompanhamento de atividades, de responsabilidade da Scrum Master, se encontra na imagem adiante, que contém o gráfico Burndown gerado pela equipe (onde o eixo X são os dias trabalhados na sprint e os valores do eixo Y representam as entregas e esforços realizados com o passar do tempo), incluindo as atividades desenvolvidas e seus responsáveis.

<div align="center">
<img src="https://user-images.githubusercontent.com/69374340/168503391-48bbd6d4-9a62-4391-9894-4a12f5dcf4c7.png" alt="Gráfico de Burndown da sprint 02">
</div>  
    
<details>
   <summary>Clique aqui para ver as tarefas realizadas na sprint</summary>
   <img src="https://user-images.githubusercontent.com/69374340/168503748-b0ff325e-ec64-4b22-9293-3c958a21f6ff.png">
</details>

→ [Voltar ao topo](#topo)
    
<span id="links">
    
## :link: Links úteis

- Site do projeto: [https://help-duck.netlify.app/](https://help-duck.netlify.app/) (usuário exemplo - email: `user@gmail.com`, senha: `1357`)
- Tags foram geradas nos seguintes repositórios para simbolizar o fim da 2ª sprint:
  - Repositório do site: [clique aqui para acessar "help-duck-web"](https://github.com/The-Bugger-Ducks/help-duck-web)
  - Microsserviço de usuários e equipamentos: [clique aqui para acessar "help-duck-register"](https://github.com/The-Bugger-Ducks/help-duck-register)
  - Microsserviço de chamados: [clique aqui para acessar "help-duck-tickets"](https://github.com/The-Bugger-Ducks/help-duck-tickets)

→ [Voltar ao topo](#topo)
