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