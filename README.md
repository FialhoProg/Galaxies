<h1>Projeto Galáxias</h1>

Este projeto é uma página web simples que apresenta algumas das maiores galáxias conhecidas e curiosidades sobre elas. O layout da página foi criado utilizando **CSS Grid**, destacando o uso deste poderoso método de layout.

<h2>Índice</h2>

- [Visão Geral](#visão-geral)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Uso do CSS Grid](#uso-do-css-grid)
- [Fontes e Créditos](#fontes-e-créditos)

## Visão Geral

O projeto consiste em uma única página HTML (`index.html`) estilizada com um arquivo CSS externo (`style.css`). Ele apresenta uma lista de galáxias, cada uma com uma imagem e uma breve descrição.

## Estrutura do Projeto

- **index.html**: Contém a estrutura HTML da página, com elementos como `header`, `main` e `div` para os cartões de galáxias.
- **style.css**: Contém o estilo CSS utilizado na página, incluindo o layout de grid e a estilização dos elementos.
- **assets/**: Pasta que contém as imagens das galáxias.

### index.html

O arquivo `index.html` define a estrutura básica da página. Ele inclui:

- **Doctype e Metatags**: Define o tipo de documento e as configurações de codificação e viewport.
- **Links para Fontes e CSS**: Inclui links para as fontes do Google Fonts e para o arquivo de estilo CSS.
- **Header**: Contém um título (`h1`) e uma descrição (`p`) sobre as galáxias.
- **Main**: A seção principal onde os cartões de galáxias são exibidos. Cada cartão é uma `div` com uma imagem, um título (`h2`) e um parágrafo (`p`).

### style.css

O arquivo `style.css` aplica os estilos visuais à página. Principais pontos incluem:

- **Reset e Box-Sizing**: Define margens e paddings para zero e aplica `box-sizing: border-box` a todos os elementos.
- **Body**: Estiliza o corpo da página com fundo escuro e usa CSS Grid para centralizar o conteúdo.
- **Header**: Define a estilização do título e da descrição.
- **Main**: Utiliza CSS Grid para criar um layout de três colunas, com espaçamento entre os cartões.
- **Cards**: Estiliza as `div` dos cartões com fundo, bordas arredondadas e overflow hidden para garantir que o conteúdo se ajuste dentro do cartão.

## Uso do CSS Grid

A página faz uso extensivo do **CSS Grid** para organizar o layout dos elementos de forma responsiva e flexível. O CSS Grid é utilizado principalmente na seção `main` para distribuir os cartões das galáxias em um layout de três colunas com espaçamento uniforme. 

## Fontes e Créditos

- As fontes utilizadas no projeto são fornecidas pelo Google Fonts: [Mulish](https://fonts.google.com/specimen/Mulish)
- As imagens das galáxias são de domínio público ou licenciadas para uso educacional.
- O design do proejto foi desenvolvido pela equipe da RocketSeat


Desenvolvido por Breno Fialho (https://github.com/FialhoProg)
