# HTML

## História

Em 1991 Tim Berners-Lee criou o **HTML**, uma **linguagem de marcação**, para melhorar a comunicação entre ele e seus colegas de trabalho. Desde então surgiram 5 versões e o HTML se tornou a **base da web.**

- HTML 1 - 1991
- HTML 2 - 1995
- HTML 3 - 1997
- HTML 4 - 1997
- HTML 5 - 2014

## Estrutura básica 

A primeira linha do documento deve ser o `<!DOCTYPE>`, ela aponta para o naveador que ele está lidando com um arquivo do tipo HTML5.

A tag `<html>` é a raiz do documento, todos os elementos devem estar dentro dela. Nela nós informamos ao nevegador qual o idioma do documento, através do atributp *lang*, para o português usamos o pt-BR.

A taf `<head>` contém elementos que serão lidos pelo navegador, como os metadados e o título da página com a tag *title*.

A tag `<body>` contém todo o conteúdo visível ao usuário como textos, imagens e vídeos.

~~~html
<!DOCTYPE html>
<html>
    <head>
        <meta>
        <title></title>
    </head>
    <body>
    </body>
</html>
~~~

## Semântica

Durante muitos anos o elemento padrão do HTML era a div, todo conteúdo era construído baseado nela. Em 2014 com a versão 5 do HTML ocorreram várias mudanças importantes, como performance e acessibilidade. 

A semântica permite descrever mais precisamnte o conteúdo, agora um bloco de texto não é apenas uma div, é um article e tem mais significado assim.

`<section>` representa uma seção genérica de conteúdo quando não houver um elemento mais específico para isso.

`<header>` é o cabeçalho da página ou de uma seção da página, normalmente contém logotipos, menus e campos de busca.

`<article>` representa um conteúdo independente e de maior relevância dentro de uma página. Um article pode conter outros elementos como header, cabeçalhos, parágragos e imagens.

`<aside>` é uma seção que engloba conteúdos relacionados ao conteúdo principal. Normalmente são representadas como barras laterais.

`<footer>` representa o rodapé do conteúdo ou parte dele, pois é aceito dentro de vários elementos. 

`<h1><h6>` eles não foram criados na versão 5 do HTML e nem são específicas para semântica, mas servem para esse propósito. Sâo utilizados para marcar a importância dos títulos, sendo o h1 o mais importante e o h6 o menos. 

## Textos e links

Para textos utilizamos o elemento <p>. O `<p>` representa um parágrafo, mas ele não suporta apenas texto, é possível adicionar imagens, código, vídeos e vários outros tipos de conteúdo dentro dele.

Outro elemento interessante é o `<a>`, que significa *anchor*, representa um hyperlink, interliga vários conteúdos e páginas. 

O `<href>` representa o hyperlink para onde a anchor aponta, podendo ser uma página do site, externa, email e até mesmo telefone. 

## Imagens 
A web também é feita de imagens e elas são representadas com o elemento `<img>`. Esse elemento contém os atributos scr e alt. O src é obrigatório e guarda o caminho para a imagem. O alt é opcional mas é altamente recomendado para melhorar a acessibilidade, ele mostra a descrição da imagem. 

## Listas

As listas servem para agrupar uma coleção de itens.

 O elemento `<ul>` cria uma lista não ordenada, onde as ordem dos elementos não é importante e é representada com pontos, círculos ou quadrados. 

 O `<ol>` serve para criar lista ordenada, a ordem é importante, são representadas com números, algarismos romamos ou letras.

 O elemento `<li>` é um item dentro das listas. Pode conter vários tipos de conteúdos como parágragos, imagens e até outras listas. 
