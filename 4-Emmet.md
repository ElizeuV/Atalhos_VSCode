## Criando tags (atalhos): hdr, btn, ftr etc...
````

````
## Criando elemento com uma classe, Exemplo:
````
    p.text -> <p class="text"></p>
    div.container -> <div class="container"></div>
````

## Elementos com muitas classes:
````
    div.primeira-classe.segunda-classe -> <div class="primeira-classe segunda-classe"></div>
    ftr.classe-1.classe-2.calsse-3  -> <footer class="classe-1 classe-2 calsse-3"></footer>
    p.paragrafo-principal.negrito -> <p class="paragrafo-principal negrito"></p>
    .classe -> <div class="classe"></div>
````

## Criando elementos com ids
````
    div#id-1 -> <div id="id-1"></div>
    hdr#cabecalho -> <header id="cabecalho"></header>
````

## Elemento com classe e id
````
    ftr.use-classe#use-id -> <footer class="use-classe" id="use-id"></footer>
````

## Conteúdo dentro do elemento
````
span{Meu texto} -> <span>Meu texto</span>
h1.titulo-1{Título} -> <h1 class="titulo-1">Título</h1>
hdr.cabecalho{Este é o cabeçalho}#hdr-1 -> <header class="cabecalho" id="hdr-1">Este é o cabeçalho</header>
````

## Criando múltiplos elementos
````
h1+p+div -> 
<h1></h1>
<p></p>
<div></div>

h1.titulo{Este é o título H1}+p+div#divisao-01 ->
<h1 class="titulo">Este é o título H1</h1>
<p></p>
<div id="divisao-01"></div>
````

## Criando elementos aninhados
> 1
````

nav.navegacao>h1.titulo-1{Título}+ul.>li>a.links*3 ->
<nav class="navegacao">
    <h1 class="titulo-1">Título</h1>
    <ul class="">
        <li>
            <a href="" class="links"></a>
            <a href="" class="links"></a>
            <a href="" class="links"></a>
        </li>
    </ul>
</nav>
````
> 2
````
nav.navegacao>h1.titulo-1{Título}+ul.>li>a.links{Descrição do link}*3
<nav class="navegacao">
    <h1 class="titulo-1">Título</h1>
    <ul class="">
        <li>
            <a href="" class="links">Descrição do link</a>
            <a href="" class="links">Descrição do link</a>
            <a href="" class="links">Descrição do link</a>
        </li>
    </ul>
</nav>
````



