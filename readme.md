<h1>Galeria de seleção com pop up dinâmicos</h1>

<h3>
<a href="https://jsfiddle.net/phscezario/24h579o1/4/" target="new">Veja Aqui</a>
</h3>

<h3>O que precisa:</h3>

- Você deve colocar o tributo rel como "showpopup" e um id em todos os elementos que forem abrir uma pop-up.<br>
Exemplo: < div rel="showpopup" id="item2" >

- As pop-ups devem estar dentro de um container com a id="popup-container".<br>
Exemplo: < div  id="popup-container" >

- Cada pop-up precisa ter a class="popup-window" e um atributo data-id igual o id do elemento que ele vai abrir.<br>
Exemplo: < div class="popup-window" data-id="item2" >


<h3>Como funciona?</h3>
O script vai varificar e copiar todos elementos do container e adicionar a um array, depois disso vai removelo do DOM antes mesmo que ele carregue todos os itens, deixando assim a pagina mais leve.<br>
Quando clicar em algum elemento o script achará o elemento no array e retornará ele na tela.



