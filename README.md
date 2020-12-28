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
</ul>

## Funcionalidades

<ul>
  <li>Faz uma pesquisa na API no opentdb e no gravatar e renderiza a fim de montar um game.</li><br>
  <li>Ao pesquisar, aparecerá uma lista de no máximo 50 resultados onde aparecerão apenas 2 linhas com 6 produtos cada e o usuário poderá controlar com os botões Up e Down</li><br>
  <li>Search
    <ul>
      <li>Pesquisa produtos de acordo com a categoria ou a query digitada na barra de buscas.</li>  
      <li>Lista os produtos e o usuário pode adicoina-los ao carrinho uma vez.</li> 
    </ul><br>
  </li>
  
  <li>Product Details
    <ul>
      <li>Pode ser acessado através do Search, clicando na imagem do produto.</li>  
      <li>Pode adicionar ao carrinho uma vez e deixar um comentário.</li> 
    </ul><br>
  </li>
  
  <li>Toogle Shopping Cart
    <ul>
      <li>Mostra os produtos adicionados ao carrinho, o usuário pode adicionar ou diminuir a quantidade, caso seja 0 o produto saírá da lista.</li>  
      <li>O usuário pode acessar a tela de Checkout pelo botão Finalizar Compra</li> 
    </ul><br>
  
   <li>Checkout
    <ul>
      <li>
        Mostra os produtos adicionados ao carrinho, o usuário deve preencher com suas informações e forma de pagamento para conseguir acessar a proxima tela.           </li>  
    </ul><br>
  </li>
  
   <li>Confirmation
    <ul>
      <li>Mostra as informações principais da compra para a confirmação do usuário.</li>  
    </ul><br>
  </li>
</ul>

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
