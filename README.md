# Exercícios CSS

## Lista de Exercícios sobre Fontes, Textos, e Box Model

Faça um clone deste repositório e siga pelas instruções deste arquivo [README.md](http://README.md) para executar os exercícios.

- Execute os exercícios na ordem. Eles são dependentes.
- Depois de clonar o repositório abra o arquivo `index.html` no seu editor de código e abra também no seu navegador.
- Identifique o que cada tag do HTML representa na página. Isso tornará mais fácil você saber **O que é um Post Destaque** por exemplo.
- Comente o HTML usando `<!-- -->` , se necessário.

**Boa sorte! 🍀**

---

### 🔵 Exercício 1

Clone o repositório do GitHub localmente: https://github.com/cesartera/css-fontes-texto.git 
Você pode fazer isso usando a CLI (Command Line Interface) ou até mesmo direto pelo site do GitHub e fazendo o download localmente na sua máquina.

### 🔵 Exercício 2

- Na pasta raiz do repositório clonado crie a estrutura de arquivos para adicionar um arquivo **style.css**
- Adicione uma tag `<link>` no arquivo **index.html** para que ele passe a identificar os estilos definidos no arquivo **style.css**

### 🔵 Exercício 3

- Vá até o [Google Fonts](https://fonts.google.com)  e escolha:
    - A fonte Open Sans para usar em Headers (tags `<h1>` a `<h6>`)
    - A fonte PT Sans para usar em Parágrafos, Links e Botões (tags `<p>` , `<a>` e `<button>`)
- Importe essas fontes no arquivo **style.css**
- Defina Open Sans para as tags header contidas no projeto inicial.
- Defina PT Sans para as tags parágrafos, links e botões contidas no projeto inicial.

### 🔵 Exercício 4

Defina o tamanho para as Fontes conforme a tabela:

| Elemento | Tamanho |
| --- | --- |
| h1 | 36px |
| h2 | 24px |
| h3 | 20px |
| p | 16px |
| a | 16px |
| button | 16px |

### 🔵 Exercícios 5

Use a propriedade `text-decoration` para:

- Deixar todas as tags `<a>` sem nenhum sublinhado.
- Deixar todas as tags `<h3>` que são Títulos de Post de Blog com sublinhado.
**Importante:** As tags h3, dentro da tag `<aside>` não devem ter sublinhado.

### 🔵 Exercícios 6

Use a propriedade `text-aling` para:

- Deixar as todas imagens que estão dentro das tags `<article>` alinhadas ao centro.
- Deixar todas as tags `<p>` que são legendas das imagens alinhadas ao centro.
- Deixar todas as tags `<h3>` que são títulos de post, alinhados à esquerda.
- Deixar todas as tags `<p>` que são conteúdos de post, alinhados à esquerda.

### 🔵 Exercício 7

- Defina a largura da tag `<header>` para 80% do tamanho da página.
- Adicione margens innternas (*paddinng*) à esquerda e à direita da tag `<header>`. Ambas as margens com 10% do tamanho da página.
- Adicione margens internas (*padding*) de 5% acima e abaixo da tag `<header>`
- Defina a largura de todos os artigos para 60% do tamanho da página.
- Adicione margens à esquerda e à direita dos artigos. Ambas as margens com 20% do tamanho da página.

### 🔵 Exercício 8

- Defina a cor de fundo da tag `<nav>` para preto HEX(#000000).
- Defina a cor tags `<a>` que estão dentro da tag `<nav>` para branco HEX(#FFFFFF).
- Defina a cor de fundo da tag `<header>` para o cinza HEX(#BFBFBF).
- Defina a cor da tag h3 do artigo com a classe destaque para o azul HEX(#95BBDF).

### 🔵 Exercício 9

- Defina o espaçamento interno da tag `<nav>` para 20px.
- Defina as margens laterais das tags <a> que estão dentro da tag <nav> para 10px.
**Importante: As margens superiores e inferiores devem permanecer em 0.**
    

### 🔵 Exercício 10

Para fazer com que o `<aside>` fique do lado direito, vamos usar a propriedade **[float](https://developer.mozilla.org/pt-BR/docs/Web/CSS/float).**

- Defina a largura da tag `<aside>` para 20% do tamanho da tela.
- Defina as margens da tag `<aside>` para 5% do tamanho da tela.
- Defina a propriedade `float` para que a tag `<aside>` flutue à direita.
