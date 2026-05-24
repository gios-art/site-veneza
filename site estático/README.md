# Guia Turístico de Veneza

Projeto acadêmico de site estático desenvolvido com HTML5 para apresentar um guia turístico sobre Veneza, na Itália. O conteúdo foi separado em três páginas independentes para deixar a navegação simples e a estrutura mais fácil de explicar na apresentação.

## Visão Geral

O foco do trabalho é demonstrar organização de conteúdo com semântica HTML. Como o site é estático, ele não depende de back-end, banco de dados ou JavaScript: o navegador apenas interpreta o HTML e monta a interface.

## Estrutura Das Páginas

### principal.html

Página inicial do projeto. Ela apresenta o tema e concentra a introdução geral sobre Veneza.

- `header` para o título e o menu principal;
- `main` como área central do conteúdo;
- `section` e `article` para separar introdução e curiosidades;
- `blockquote` para a citação;
- `aside` para uma observação complementar ao viajante.

Essa página mostra a hierarquia básica de um site informativo: entrada, contexto e conteúdo adicional.

### pontos.html

Página dedicada aos principais pontos turísticos e às imagens ilustrativas.

- `header` com navegação e título;
- `article` para cada atração, tratando cada bloco como conteúdo independente;
- `img` com `alt` descritivo, importante para acessibilidade;
- `ul` para listar outros locais relevantes.

Aqui o uso de `article` faz sentido porque cada atração é uma unidade de informação separada.

### food.html

Página voltada à gastronomia veneziana. Ela é a mais útil para mostrar estruturas mais técnicas do HTML.

- `table` com `caption`, `thead`, `tbody`, `th` e `td` para organizar os pratos;
- `fieldset` e `legend` para agrupar os campos do formulário;
- `label`, `input`, `select`, `textarea` e `button` para a interação com o usuário;
- `aside` para uma curiosidade extra.

Essa página reforça dois pontos importantes em HTML: estrutura tabular e organização semântica de formulário.

## Estrutura Técnica

O projeto usa HTML puro, priorizando legibilidade e semântica. Os principais elementos empregados foram:

- `header`, `nav`, `main`, `section`, `article`, `aside` e `footer`;
- `blockquote` e `q` para citações;
- `ul` para listas não ordenadas;
- `table` para dados tabulares;
- `form` para captura de dados;
- links internos entre as três páginas;
- links externos para referências e sites de apoio.
