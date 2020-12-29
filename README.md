# Trivia-Game
<img align ="left" src="/src/img/app-image/app-image1.png" width="400" alt="imagem-1" />
<img align ="center" src="/src/img/app-image/app-image2.png" width="400" alt="imagem-2"/>
<img align ="left" src="/src/img/app-image/app-image3.png" width="400" alt="imagem-3" />
<img align ="center" src="/src/img/app-image/app-image4.png" width="400" alt="imagem-4"/>

Link da pasta das imagens <a href="https://github.com/Rods27/frontend-online-store/tree/master/src/img/app-image/">aqui.</a>

## Feedback 

Ficarei bem agradecido caso queira me dar um feedback costrutivo, caso queira meus contatos estarão abaixo!

Email: rods.leite27@gmail.com e <a href="https://linkedin.com/in/rodrigoleite27">Linkedin</a>

## Observações

<ul>
  <li>Os Settings ainda não foi implementado, o botão é por questão de layout</li>
  <li>A ordem das perguntas está a mesma, não tive tempo de arrumar isso</li>
  <li>Mobile não Implementado</li>
  <li>As perguntas são pegas pela API <a href="https://opentdb.com/a">opentdb</a> e a foto de perfil pelo <a href="https://pt.gravatar.com/">Gravatar</a>.</li>
</ul>

## Funcionalidades

<ul>
  <li>Faz uma pesquisa na API no opentdb e no gravatar e renderiza a fim de montar um game.</li><br>
  <li>Caso acerte mais de 3 perguntas, receberá um feedback positivo, caso contrário um feedback construtivo, no final, pode jogar denovo ou ir para a tela de ranking de jogadores.</li><br>
  <li>Login
    <ul>
      <li>Faz um crivo de formato no email, e nome</li>  
      <li>O nome fica salvo no Ranking</li> 
    </ul><br>
  </li>
  
  <li>Game
    <ul>
      <li>Renderiza uma pergunta com apenas uma possivel resposta, caso acerte será calculado a pontuação pelo tempo</li>  
      <li>O tempo pode acabar e o jogador não recebera pontos</li> 
    </ul><br>
  </li>
  
  <li>Feedback
    <ul>
      <li>Renderiza a quantidade de pontos e acertos do usuário</li>  
      <li>O usuário pode jogar denovo ou ir para o Ranking</li> 
    </ul><br>
  
   <li>Ranking
    <ul>
      <li>
        Renderiza o nome a pontuação e o perfil de todos os jogadores por ordem decrescente
      </li>  
    </ul><br>
  </li>

## Pré Requisitos
<ul>
  <li>Npm</li>
  <li>Node</li>
  <li>React</li>
  <li>React-thunk</li>
  <li>React Redux</li>
</ul>

### Instalando
Após intalar Node e Npm: 
React<br><br>
`npm i react`<br><br>
Redux<br><br>
`npm i redux`<br><br>
Redux-Thunk<br><br>
`npm i redux-thunk`<br><br>
