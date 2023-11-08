# Site da Pizzaria Teste

O site da Pizzaria Teste foi criado com HTML, CSS e JavaScript para oferecer uma experiência de escolha e compra de pizzas online. Abaixo está uma explicação simplificada da estrutura do código e funcionalidades do site.

## Estrutura do Site (HTML)
O arquivo `index.html` é a estrutura principal do site, onde estão definidos:

- **Cabeçalho (Header):**
  - Apresenta o título do site (Pizzaria Teste) e inclui a referência a um arquivo de estilo (`style.css`).

- **Corpo da Página (Body):**
  - Divide-se em seções principais:
    - **Área de Listagem de Pizzas (main):**
      - Exibe uma lista de pizzas disponíveis para compra, onde cada pizza possui detalhes como nome, imagem, preço e descrição.
    - **Carrinho de Compras (aside):**
      - Mostra as pizzas adicionadas ao carrinho, com opções para aumentar ou diminuir a quantidade de cada item, subtotal, desconto e total a pagar.
    - **Área de Detalhes da Pizza (pizzaWindowArea):**
      - Apresenta os detalhes da pizza selecionada, permitindo ao usuário escolher o tamanho, quantidade e adicioná-la ao carrinho.

## Estilos (CSS)
O arquivo `style.css` é responsável pelo design e estilo do site, aplicando formatações visuais e de layout para uma melhor experiência do usuário.

## Funcionalidades (JavaScript)
Os arquivos `pizzas.js` e `script.js` contêm funcionalidades como:

- **Listagem de Pizzas:**
  - Utiliza dados do arquivo `pizzas.js` para exibir as pizzas disponíveis com detalhes como imagem, preço e descrição.
- **Modal de Detalhes da Pizza:**
  - Permite visualizar os detalhes da pizza selecionada, escolher o tamanho e quantidade antes de adicioná-la ao carrinho.
- **Manipulação do Carrinho de Compras:**
  - Adicionar, remover e atualizar itens no carrinho, exibindo o subtotal, desconto e o total a pagar.

## Estrutura de Dados (pizzas.js)
O arquivo `pizzas.js` contém uma lista de objetos, onde cada objeto representa uma pizza com propriedades como ID, nome, imagem, preço, tamanhos disponíveis e descrição.

## Principais Funcionalidades do JavaScript (script.js)
O arquivo `script.js` implementa as funcionalidades principais do site, incluindo:

- Listagem dinâmica de pizzas a partir do arquivo `pizzas.js`.
- Modal de detalhes da pizza e interações para adicionar ao carrinho.
- Controle do carrinho de compras, inclusão, remoção e atualização de itens.
- Abertura e fechamento do menu do carrinho.

O JavaScript é essencial para o dinamismo e interatividade do site, permitindo uma experiência mais fluída e intuitiva para o usuário.

Este é um resumo simplificado do funcionamento e estrutura do site da Pizzaria Teste.
