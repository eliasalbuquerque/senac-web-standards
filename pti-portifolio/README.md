# Estrutura e Alinhamento

## HTML

### Header (`<header></header>`)

A tag `<header>` serve para conter o conteúdo que tende a ficar no cabeçalho, 
como logo, título do site, campo de pesquisa e menu principal.

```html
1. <body>
2.      <header>
3.          <h2>PORTIFÓLIO DESENVOLVEDOR WEB</h2>
4.      </header>
5. </body>
```

>**Importante:**  
>Não confunda a tag `<header>` com a tag `<head>`. Esta última é utilizada no 
início de uma página HTML, onde são colocadas as meta tags, título da página e 
outras informações.

### Aside (`<aside></aside>`)

A *tag* `<aside>` serve tanto para criar barras laterais, quanto para criar 
caixas de informação, contendo informações de apoio ao conteúdo principal.

```html
1. <body>
2.      <aside id="menu_lateral">
3.          <h1>Elias Gonçalves de Albuquerque Júnior</h1>
4.      </aside>
5. </body>
```

### Div (`<div></div>`)

A tag `<div>` não possui um significado específico. É apenas um elemento de 
divisão. Aconselha-se usar `<div>` quando você não puder utilizar nenhuma outra 
das tags semânticas.

```html
1. <aside id="menu_lateral">
2.      <div id="foto"></div>
3.      <h1>Elias Gonçalves de Albuquerque Júnior</h1>
4. </aside>
```

### Nav (`<nav></nav>`)

A tag `<nav>` foi criada com a finalidade de indicar qual é o menu principal do 
site.

```html
1. <aside id="menu_lateral">
2.      <div id="foto"></div>
3.      <h1>Elias Gonçalves de Albuquerque Júnior</h1>
4.      <nav>
5.          <h3>CONTATO</h3>
6.          <ul>
7.              <li>Linkedin</li>
8.              <li>Instagram</li>
9.              <li>e-mail</li>
10.             <li>Whatsapp</li>
11.         </ul>
12.     </nav>
13. </aside>
```

### Main (`<main></main>`)

A *tag* `<main>` serve para definir o conteúdo principal da página. Não importa
o tipo de informação, deve sempre ficar dentro da *tag* `<main>` quando esta for 
utilizada no código. E as informações que são comuns à todas as páginas do site, 
como o menu principal, logo, campo de busca, copyright, etc., não devem aparecer 
dentro desta *tag*.

```html
1. <main>
2. <!-- aqui iremos colocar as áreas da página e seu respectivo conteúdo -->
3. </main>
```

>**Importante:**  
>Só pode existir uma tag `<main>` na página e ela nunca deve ser uma tag filha 
das tags `<section>`, `<article>`, `<nav>`, `<footer>`, `<header>` e `<aside>`.

### Section (`<section></section>`)

A tag `<section>` serve para dividir cada sessão do conteúdo.

```html
1. <main>
2.      <section>
3.          <!-- conteúdo da sessão -->
4.      </section>
5. </main>
```

### Footer (`<footer></footer>`)

A *tag* `<footer>` serve para indicar o texto do rodapé, seja
de toda a página ou de cada seção (*section*) da página. Normalmente
serve para conter informações institucionais e de copyright.

```html
1. <footer>
2.      <p>Desenvolvido por (seu nome) – Todos os direitos reservados</p>
3. </footer>
```

## CSS

### Margin

Essa propriedade serve para criar uma margem, ou seja, um espaço ao redor do 
elemento. Podemos controlar cada lado separadamente:

```css
1. margin-top: 32px;
2. margin-right: 32px
3. margin-bottom: 32px;
4. margin-left: 32px;
```

Também podemos escrever de forma resumida:

```css
1. margin: 32px 32px 32px 32px;
```

Ou, ainda, desta forma, mas somente quando todos os lados possuírem a mesma 
medida:

```css
1. margin: 32px;
```

### Padding

Essa propriedade serve para colocar um preenchimento na área interna do elemento.

```css
1. padding-top: 48px;
```

Explicar:

- width
- height
- clear
- float
- px
- %