# HTML e CSS: ambientes de desenvolvimento, estrutura de arquivos e tags
__Figma__
https://www.figma.com/design/rCMjRsLl0ZbMtTFJBi038t/Portfolio---Curso-1-(Copy)?node-id=1-11&t=aiUq8oTF8NI17qak-1

__Módulo 02__
* [W3 Schools](https://www.w3schools.com/html/)
* Meta-informações: Tags que possui informações sobre a página.
* [Quircks Mode](https://developer.chrome.com/docs/lighthouse/best-practices/doctype?utm_source=devtools&hl=pt-br)
* [Extensões para o vscode](https://www.alura.com.br/artigos/extensoes-vs-code-descubra-as-mais-usadas)
* [Comunidades front-end](https://www.alura.com.br/artigos/principais-comunidades-front-end)
* [Estrutura básica do HTML](https://www.alura.com.br/artigos/o-que-e-html-suas-tags-parte-1-estrutura-basica?utm_source=gnarus&utm_medium=timeline)

### A estrutura básica do HTML  
Para criar um arquivo HTML funcional devemos seguir um padrão de construção, utilizando um conjunto de elementos, ou seja, os hipertextos, que se conectam entre si formando a página. Como já visto anteriormente, os elementos HTML ou também chamados de tags HTML, são utilizados para informar ao navegador que tipo de estrutura é essa que está sendo construída, podendo ser títulos, parágrafos, imagens, links, entre outros.

Um exemplo prático dessa estrutura básica seria:
``` HTML 5
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>
```

__Módulo 03__
* [Emmet](https://docs.emmet.io/)

### [Tags semânticas](https://developer.mozilla.org/pt-BR/docs/Glossary/Semantics)
tags semânticas, que são tags descritivas sobre o conteúdo que armazenam, como é o caso das tags ``` <header>, <main> e <footer>```, que conhecemos nessa aula. Elas servem tanto para otimizar a leitura pelos navegadores, como pelas pessoas desenvolvedoras que vão fazer a manutenção do código.

__Módulo 04__
* [Documentação](https://www.w3schools.com/css/default.asp)

__Módulo 05__
### Sites para paletas de cores
* [Coolors](https://coolors.co/)
* [Adobe Color](https://color.adobe.com/pt/create/color-wheel)
* [Color Hunt](https://colorhunt.co/)
* [Color Tool](https://m3.material.io/styles/color/system/overview)

### Tag ```<span>```

Podemos destacar o texto utilizando a tag ```<strong>```, porém existe outra tag que também é muito utilizada para isso que é a tag ```<span>```, diferente da strong a span não deixa em negrito por padrão, mas é uma ótima forma de marcar trechos do texto em HTML. Veja:

```html
<h1>Formação de <span>Front-end</span></h1>
```
```css
h1{
            font-weight: bold;
}
 
span{
            color: #22D4FD;
            border: 1px solid #22D4FD;
            padding: 10px;
}
```

#### Resultado
![alt text](imagens/image.png)

## Complemento
* [HTML, CSS e JavaScript - As diferenças - (Gratuito, Português, Texto)](https://www.alura.com.br/artigos/html-css-e-js-definicoes)
* [HTML para iniciantes: o que é e como funciona - (Gratuito, Português, Texto)](https://www.hostinger.com.br/tutoriais/o-que-e-html-conceitos-basicos)
* [Introdução às tags HTML - (Gratuito, Inglês, Tutorial)](https://www.w3schools.com/tags/)
* [Tutorial de HTML Básico - MDN Web Docs (Gratuito, Português, Online)](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/HTML_basics)
* [Estrutura básica de uma página HTML - HTML Dog (Gratuito, Inglês, Online)](https://htmldog.com/guides/html/beginner/)
* T[utorial de acessibilidade na web - WebAIM (Gratuito, Inglês, Online)](https://webaim.org/intro/)
* [Modo Quirks e padrões em navegadores - MDN Web Docs (Gratuito, Inglês, Online)](https://developer.mozilla.org/en-US/docs/Web/HTML/Quirks_Mode_and_Standards_Mode)
* [Uso de extensões no Visual Studio Code - Visual Studio Code Docs (Gratuito, Inglês, Online)](https://code.visualstudio.com/docs/editor/extension-gallery)
* [Live Server Extension para Visual Studio Code - GitHub (Gratuito, Inglês, Online)](https://github.com/ritwickdey/vscode-live-server)
* [UX/UI Design: Fundamentos para a qualidade na interface de usuário - Interaction Design Foundation (Gratuito/Pago, Inglês, Online)](https://www.interaction-design.org/literature/topics/ux-design)
* [Dicas de CSS (Gratuito, Inglês, Online)](https://css-tricks.com/guides/)
* [Guia de estruturação de páginas HTML com semântica - MDN Web Docs (Gratuito, Inglês, Online)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
* [Utilizando Emmet para acelerar o desenvolvimento HTML - CSS-Tricks (Gratuito, Inglês, Online)](https://css-tricks.com/emmet/)
* [Introdução ao HTML5 e tags semânticas - HTML.com (Gratuito, Inglês, Online)](https://html.com/html5/)
* [Uso efetivo de tags âncora em HTML - W3Schools (Gratuito, Inglês, Online)](https://www.w3schools.com/html/html_links.asp)
* [Como inserir Imagens em HTML - MDN Web Docs (Gratuito, Inglês, Online)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)
* [Práticas recomendadas para design responsivo - Smashing Magazine (Gratuito, Inglês, Online)](https://www.smashingmagazine.com/2011/01/guidelines-for-responsive-web-design/)
* [Como utilizar folhas de estilo em cascata (CSS) - MDN Web Docs (Gratuito, Inglês, Online)](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Guia de cores e fontes em CSS - Adobe Color (Gratuito, Inglês, Online)](https://color.adobe.com/create/color-wheel)
* [Hipsters ponto tech episódio #09 CSS: cansei de ser simples - (Gratuito, Português, Áudio)](https://www.hipsters.tech/css-cansei-de-ser-simples-hipsters-09/)


# HTML e CSS: Classes, posicionamento e Flexbox
__Módulo 01__  
[Class](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/class): O atributo **class** permite ao CSS selecionar e acessar elementos específicos através dos seletores de classe.  
[Dicas de nomes de classes](https://www.alura.com.br/artigos/nomes-de-classes-no-css)    
[Seletores](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Selectors)  
[Reset CSS](https://www.alura.com.br/artigos/o-que-e-reset-css)

__Módulo 02__  
[Box-sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)  
[Viewport](https://www.alura.com.br/artigos/guia-de-unidades-no-css): Em computação gráfica, a viewport é a porção de área visível de um plano e é utilizada como unidade de medida no CSS para criar páginas Web 100% responsivas. Em outras palavras, a viewport varia de dispositivo para dispositivo, por exemplo em computadores, tablets e celulares, cada tela possui dimensões diferentes e enquanto uma página não responsiva apresentaria os elementos desproporcionais, uma página responsiva utilizando viewport teria seus elementos adequados a cada proporção.   
[Flexbox](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/CSS_layout/Flexbox)  
[Guia Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

__Módulo 03__  
* [Google fonts - guia](https://developers.google.com/fonts/docs/getting_started?hl=pt-br)  
* [ Divs](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/div): A tag _div_ define uma divisão em um documento HTML e costuma ser usada como um contêiner para outros elementos, o que ajuda na estilização do bloco. Por esse motivo, a <div> é frequentemente utilizada quando precisamos agrupar elementos sem usar as tags semânticas do HTML. Isso acontece porque a <div> não tem valor semântico. Portanto, não significa nada para os navegadores e mecanismos de pesquisa.
Além do mais, por ser muito utilizada para agrupar elementos, acaba facilitando na organização das informações nos layouts. Dessa forma, pode ser formatada e manipulada organicamente via CSS. Geralmente vem acompanhado de atributos de ID e classe para facilitar essa organização e formatação.  
* [Border](https://www.alura.com.br/artigos/css-border-estilizando-bordas-elementos-css): A propriedade _border_ é responsável pelas bordas dos elementos HTML. Ao inserir um elemento em um documento HTML, há várias possibilidades de estilizar sua borda. Você pode utilizar estilos que a propriedade já possui, além de poder também alterar sua cor, espessura e até mesmo seu formato! Utilizando apenas o poder do CSS!
* [Gap](https://css-tricks.com/almanac/properties/g/gap/): A propriedade gap não é exclusiva do Flexbox, porém é utilizada quase sempre em conjunto com ele. Ela especifica no CSS o tamanho dos espaços entre linhas e colunas em layouts de grid, flex e multi-column. Sua sintaxe é bem simples e ela aceita um ou dois valores.  
* [Propriedades do CSS](https://www.alura.com.br/artigos/css-guia-do-flexbox)

## Referências
https://www.alura.com.br/artigos/css-seletores-avancados-aplicacoes-web
https://www.alura.com.br/artigos/comecando-a-organizar-seu-css
https://www.alura.com.br/artigos/criando-componentes-css-com-padrao-bem
https://www.alura.com.br/artigos/entendendo-como-funciona-box-model-e-o-box-sizing
https://www.alura.com.br/artigos/css
https://www.alura.com.br/artigos/o-que-e-reset-css
https://www.alura.com.br/artigos/organizando-o-css-no-seu-projeto
https://www.alura.com.br/artigos/guia-de-unidades-no-css
https://cursos.alura.com.br/forum/topico-duvida-viewport-271522
https://www.alura.com.br/artigos/entendendo-como-funciona-box-model-e-o-box-sizing
https://cursos.alura.com.br/forum/topico-qual-a-funcao-do-box-sizing-border-box-34779
https://www.alura.com.br/artigos/css-guia-do-flexbox
https://www.alura.com.br/conteudo/css-flexbox-layouts-responsivos
https://www.alura.com.br/apostila-html-css-javascript/05CA-trabalhando-com-tamanhos-e-espacamento
https://www.alura.com.br/apostila-html-css-javascript/13CA-medidas-relativas-em-rem
https://cursos.alura.com.br/forum/topico-duvida-importacao-da-fonte-281161
https://cursos.alura.com.br/forum/topico-google-fonts-link-ou-import-130517
https://www.alura.com.br/artigos/tailwind-adicionando-fontes-customizadas
https://www.w3docs.com/snippets/css/how-to-import-google-fonts-in-css-file.html
https://www.wikihow.com/Use-Google-Fonts-in-CSS
https://www.alura.com.br/conteudo/tailwind-css-estilizando-pagina-classes-utilitarias
https://www.alura.com.br/apostila-html-css-javascript/10CA-treinando-display-e-nomenclatura-de-classes
https://cursos.alura.com.br/forum/topico-como-vamos-fazer-o-link-das-redes-sociais-parecer-um-botao-317242
https://cursos.alura.com.br/forum/topico-botao-dos-links-309258
https://cursos.alura.com.br/forum/topico-duvida-duvida-301971
https://cursos.alura.com.br/forum/topico-linhas-dos-links-dos-botoes-continuam-aparecendo-282291
https://cursos.alura.com.br/forum/topico-bug-erro-no-estilizando-botoes-299755
https://www.alura.com.br/conteudo/sass-css-estilizando-site

# HTML e CSS: cabeçalho, footer e variáveis CSS
[Border](https://www.w3schools.com/css/css_border.asp)  
[CSS Border](https://www.alura.com.br/artigos/css-border-estilizando-bordas-elementos-css)  
[Houver](https://www.w3schools.com/CSSref/sel_hover.php)

__Módulo 05__
Declarando [variáveis](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Using_CSS_custom_properties) no CSS:   
```css
:root{
    --cor-primaria: #000000;
    --cor-secundaria: #F6F6F6;
    --cor-terciaria: #A27B5C;
    --cor-hover: #3F4E4F;

    --fonte-primaria: "Krona One", sans-serif;
    --fonte-secundaria: "Montserrat", sans-serif;
}

/* Utilizando as variáveis*/
body{
    box-sizing: border-box;
    background-color: var(--cor-primaria);
    color: var(--cor-secundaria);
}
```

### Variáveis

#### Um armário cheio de gavetas!
Imagine que você trabalhe em uma sala de arquivos, que possui um armário muito grande e cheio de gavetas. Todos os dias, pessoas trazem seus objetos para que você guarde em uma gaveta para eles e para isso, te entregam uma etiqueta com um nome que será colado nessa gaveta que armazenará o objeto da pessoa.

Ana te entregou uma caneta e uma etiqueta com o nome: canetaDaAna, e você guardou a caneta dela em uma gaveta, onde colou a etiqueta. Ela escolheu o nome canetaDaAna, mas poderia ser qualquer outro nome e seu conteúdo poderia ser qualquer um também, como um livro, por exemplo, e não uma caneta.

Quando Ana precisar da caneta, ela irá te chamar e pedir pela canetaDaAna, e você a entregará o conteúdo da gaveta, ou seja, a caneta.

#### E como isso se relaciona com as variáveis?
O armário de gavetas no exemplo acima representa a memória do computador. Quando criamos uma variável, estamos solicitando ao computador que reserve uma “gavetinha” em sua memória para que guarde algo que precisaremos usar futuramente, e fazemos isso atribuindo um nome de variável que poderemos chamar a qualquer momento e que retornará o conteúdo que guardamos dentro dela. Esse nome pode ser um nome qualquer, no entanto sempre que solicitado ele trará como resposta aquilo que você armazenou nele.

#### O que são variáveis?
Variáveis são elementos que permitem que valores sejam manipulados ao longo da execução de seu código, através da definição de um nome para armazenar um valor que será usado repetidas vezes. Essa definição do nome e do conteúdo que será contido nele é o que nós chamamos de declaração.

Esse valor pode ser alterado ao longo do código, por isso o nome “váriavel”, exemplo:

```css
:root{
     --tamanho-da-fonte:  24px;
} 
```

Criamos no :root, ou seja, no escopo global de um código, uma variável que foi declarada com o nome __--tamanho-da-fonte__ e seu valor foi atribuído como __24px__. Toda vez que chamarmos pelo nome __--tamanho-da-fonte__, iremos obter como retorno o valor __24px__.

Variáveis são utilizadas diariamente pelas pessoas desenvolvedoras para que consigam manipular e reutilizar valores em seu código e estão presentes nas mais diversas linguagens de programação, pois são elementos base ao criar qualquer código que tenha a mínima funcionalidade. Portanto, conforme você evoluir em seus conhecimentos no desenvolvimento é certo que irá lidar muito com variáveis.

## Referências
https://www.alura.com.br/artigos/css-guia-do-flexbox
https://www.alura.com.br/conteudo/css-flexbox-layouts-responsivos
https://css-tricks.com/snippets/css/a-guide-to-flexbox/
https://www.alura.com.br/artigos/tailwind-adicionando-fontes-customizadas
https://www.alura.com.br/artigos/css-border-estilizando-bordas-elementos-css
https://www.w3schools.com/Css/css_icons.asp
https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/Dealing_with_files
https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/Dealing_with_files
https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/Dealing_with_files
https://developer.mozilla.org/pt-BR/docs/Learn/CSS/CSS_layout/Flexbox
https://www.youtube.com/watch?v=6jMqjQhHoHw
https://developer.mozilla.org/pt-BR/docs/Web/CSS/:hover
https://www.w3schools.com/howto/howto_css_transition_hover.asp
https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/CSS_basics
https://developer.mozilla.org/pt-BR/docs/Learn/CSS/Building_blocks/The_box_model
https://www.freecodecamp.org/portuguese/news/manual-do-css-um-guia-pratico-de-css-para-desenvolvedores/
https://www.creativosonline.org/pt/27-cabe%C3%A7alhos-e-rodap%C3%A9s-css-para-seu-blog-ou-site.html
https://developer.mozilla.org/pt-BR/docs/Web/CSS/Using_CSS_custom_properties
https://www.desenvolvimentoparaweb.com/css/variaveis-css-guia-pratico/
https://www.w3schools.com/css/css3_variables.asp
https://www.alura.com.br/artigos/construa-css-magico-variaveis-nativas


# HTML e CSS: trabalhando com responsividade e publicação de projetos

__Módulo 01 e módulo 02__
* [Medidas absolutas e medidas relativas](https://www.w3schools.com/cssref/css_units.php)
* [Unidades de medida no CSS](https://www.alura.com.br/artigos/guia-de-unidades-no-css)

__Módulo 03__
* [Média Queries](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_media_queries/Using_media_queries)

## [Git e GitHub](https://www.alura.com.br/artigos/o-que-e-git-github)
O Git é uma ferramenta de controle de versão de arquivos, projetos ou códigos. Já o GitHub é uma aplicação ou site onde se guardam os projetos com os arquivos dentro.

O Git é quem faz esse meio de campo entre a máquina local e o Github, o Git realiza as tarefas através de comandos, onde pode-se informar quais arquivos ou pastas serão enviadas para o GitHub.

Podemos guardar projetos nele e ainda compartilhar com outras pessoas, podendo dar sugestões e oferecer ajuda em outros projetos.  
[O que é Git e GitHub?](https://youtu.be/DqTITcMq68k?si=sn-lZTjpZe_rQRqK)
[Como usar o Git e GitHub](https://youtu.be/UBAX-13g8OM?si=FGN0-CtoEAFpBWyT)

## Readme e Repositórios
O Repositório nada mais é que uma pasta do projeto que está salva na nuvem. No caso no GitHub, criam os repositório com nome do projeto e soubimos os arquivos para dentro desta pasta. Depois de criar o repositório e colocar os arquivos dentro dele, conseguimos criar e customizar o famoso arquivo Readme.md que é onde colocamos as especificações do projeto e falar mais sobre ele, assim outras pessoas que entrarem no repositório irão ver e entender o projeto, e quais ferramentas foram utilizadas para desenvolvê-lo.

A página do arquivo [Readme.md](https://github.com/alura-cursos/readme-template) pode ser escrita utilizando o próprio HTML ou a linguagem de marcação [Markdown](https://www.alura.com.br/artigos/como-trabalhar-com-markdown), é mais comum utilizar markdown.

Exemplos:
https://github.com/alura-cursos/android-com-kotlin-personalizando-ui/blob/master/README.md
https://github.com/vanessametonini/aluramidi-curso/blob/master/README.md

Fonte: Trechos copiados da explicação feita pela página [Alura](https://www.alura.com.br/) 