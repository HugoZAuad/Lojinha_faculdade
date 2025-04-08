# 🛒 CARRINHO DE COMPRAS

📋 **Sumário**

* [🔍 Visão Geral](#-visão-geral)
* [🧱 Estrutura do Projeto](#-estrutura-do-projeto)
* [✨ Funcionalidades](#-funcionalidades)
* [🧩 Componentes](#-componentes)
* [⚙️ Requisitos](#️-requisitos)
* [🚀 Instalação e Uso](#-instalação-e-uso)
* [💡 Exemplos de Uso](#-exemplos-de-uso)


🔍 **Visão Geral**

Este projeto implementa um carrinho de compras simples utilizando HTML, Bootstrap e JavaScript. Ele exibe uma lista de produtos com seus respectivos preços, quantidades e um subtotal calculado dinamicamente.  O objetivo é demonstrar a criação de uma interface básica de carrinho de compras.


🧱 **Estrutura do Projeto**

```
CARRINHO DE COMPRAS/
└── index.html
```


✨ **Funcionalidades**

* **Exibição de Produtos:** Mostra uma tabela com informações dos produtos, incluindo nome, imagem, preço e quantidade.
* **Cálculo do Subtotal:** Calcula e exibe o subtotal dos produtos no carrinho.


🧩 **Componentes**

* **Tabela de Produtos (`<table>`)**: Exibe os produtos em formato tabular, utilizando Bootstrap para estilização.  Cada linha da tabela representa um produto.
* **Imagens dos Produtos (`<img>`)**:  Imagens dos produtos são exibidas dentro da tabela.
* **Preço e Quantidade:**  Cada produto tem seu preço e quantidade exibidos.
* **Subtotal (`<div id="subtotal">`)**:  Um elemento `div` com o id `subtotal` é usado para exibir o subtotal calculado.


⚙️ **Requisitos**

* Navegador Web moderno (Chrome, Firefox, Edge, Safari)


🚀 **Instalação e Uso**

1. **Faça o download do projeto:** Baixe a pasta `CARRINHO DE COMPRAS`.
2. **Abra o arquivo `index.html`:** Abra o arquivo `index.html` em seu navegador web.


💡 **Exemplos de Uso**

**Visualizando o Carrinho:**

Ao abrir o arquivo `index.html` em seu navegador, você verá a tabela de produtos com suas informações e o subtotal calculado.

**Exemplo de código HTML (trecho de `index.html`):**

```html
<table>
  <thead>
    <tr>
      <th>Produto</th>
      <th>Preço</th>
      <th>Quantidade</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="imagem_produto1.jpg" alt="Produto 1"> Produto 1</td>
      <td>R$ 10,00</td>
      <td>1</td>
    </tr>
    <tr>
      <td><img src="imagem_produto2.jpg" alt="Produto 2"> Produto 2</td>
      <td>R$ 20,00</td>
      <td>2</td>
    </tr>
  </tbody>
</table>
<div id="subtotal">Subtotal: R$ 50,00</div>
```

**Explicação do código:**

* A tabela (`<table>`) estrutura os dados dos produtos.
* As imagens (`<img>`) exibem as imagens dos produtos.
* O `id="subtotal"` permite a manipulação do conteúdo deste elemento via JavaScript (caso fosse implementada a atualização dinâmica do subtotal).  Neste exemplo, o valor é estático.


Este README fornece uma descrição detalhada do projeto "CARRINHO DE COMPRAS".  Ele aborda a estrutura do projeto, suas funcionalidades, componentes principais e como utilizá-lo.  A inclusão de exemplos de código e explicações claras facilita a compreensão do projeto e seu funcionamento.