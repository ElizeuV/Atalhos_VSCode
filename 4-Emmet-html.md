#### Criando tags (atalhos): hdr, btn, ftr etc...
````

````
#### Criando elemento com uma classe, Exemplo:
````
    p.text -> <p class="text"></p>
    div.container -> <div class="container"></div>
````

#### Elementos com muitas classes:
````
    div.primeira-classe.segunda-classe -> <div class="primeira-classe segunda-classe"></div>
    ftr.classe-1.classe-2.calsse-3  -> <footer class="classe-1 classe-2 calsse-3"></footer>
    p.paragrafo-principal.negrito -> <p class="paragrafo-principal negrito"></p>
    .classe -> <div class="classe"></div>
````

#### Criando elementos com ids
````
    div#id-1 -> <div id="id-1"></div>
    hdr#cabecalho -> <header id="cabecalho"></header>
````

#### Elemento com classe e id
````
    ftr.use-classe#use-id -> <footer class="use-classe" id="use-id"></footer>
````

#### Conteúdo dentro do elemento
````
span{Meu texto} -> <span>Meu texto</span>
h1.titulo-1{Título} -> <h1 class="titulo-1">Título</h1>
hdr.cabecalho{Este é o cabeçalho}#hdr-1 -> <header class="cabecalho" id="hdr-1">Este é o cabeçalho</header>
````

#### Criando múltiplos elementos
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

#### Criando elementos aninhados
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
nav.navegacao>h1.titulo-1{Título}+ul.>li>a.links{Descrição do link}*3 ->
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

#### Criando diversos elementos rapidamente
````
nav.navegacao>h1.titulo-1{Título}+ul.>li>a.links{Descrição do link}*3
````

#### Estruturas complexas de elementos
````
(div>ul*5)+(div>p*3>span) ->
<div>
    <ul></ul>
    <ul></ul>
    <ul></ul>
    <ul></ul>
    <ul></ul>
</div>
<div>
    <p><span></span></p>
    <p><span></span></p>
    <p><span></span></p>
</div>

````

#### Elementos com atributos
````
a[href="ww.google.com.br" target=_blank] -> <a href="ww.google.com.br" target="_blank"></a>

````

#### Criando form
````
form:get -> <form action="" method="get"></form>

for:post -> <form action="" method="post"></form>:post

````

#### Criando inputs
````
input:email -> <input type="email" name="" id="">

````

#### Estrutura HTML de forma rápida
````
Digitar: ! e enter
````

#### Gerador de lorem ipsum
> 1
````
lorem
````
> 2
````
lorem*5
````

#### Lorem ipsum em listas
````
ul.mylist>lorem.item*5 
<ul class="mylist">
    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur ut laboriosam, amet eum ipsa assumenda dignissimos iure nihil! Perferendis itaque enim minima quos qui a maiores ducimus explicabo dolorem exercitationem.</li>
    <li>Optio rerum delectus odio totam saepe pariatur quisquam soluta. Nobis eum saepe itaque. Quaerat, veritatis repellendus quo nihil eos minus facilis commodi porro laudantium! Nostrum quisquam hic consequatur asperiores est.</li>
    <li>Expedita distinctio minus optio fuga tempora, voluptate ut architecto iste placeat earum delectus rem deserunt a accusamus possimus exercitationem repellat non, esse et illo doloribus voluptas magnam. Temporibus, repellat ipsa!</li>
    <li>Maiores repudiandae voluptatum eveniet delectus facilis ratione in omnis, inventore nihil temporibus reiciendis, exercitationem, ad quia aperiam a cumque eos nisi illum tempora velit sed qui aliquid nemo. Exercitationem, quae.</li>
    <li>Fugiat sit facere quas. Quam explicabo, sequi obcaecati perspiciatis laboriosam molestias asperiores aspernatur ducimus exercitationem fugit commodi vel consequatur quos eum? Eligendi saepe beatae cumque, quis optio eaque accusantium labore.</li>
</ul>
````

#### Elementos com conteúdo único
> 1
````
ul>li{item $}*5
<ul>
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
    <li>item 4</li>
    <li>item 5</li>
</ul>
````
> 2
````
h${header $}*5
<h1>header 1</h1>
<h2>header 2</h2>
<h3>header 3</h3>
<h4>header 4</h4>
<h5>header 5</h5>
````

#### 
````

````



