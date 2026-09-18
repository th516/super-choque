# Projeto Super Choque - Arquivos de Dakota

## Motivação e Tema do Projeto
O objetivo principal deste projeto foi unir a admiração por um dos heróis mais clássicos dos desenhos e os estudos universitários de desenvolvimento web. Eu queria muito mostrar um pouco da história do Super Choque (Static Shock) em formato de código, documentando o universo de Dakota com o intuito prático de estudar e treinar como aplicar os recursos estruturais do HTML5.

Foi um exercício focado em transformar a narrativa de Virgil Hawkins — desde a explosão do "Big Bang" até seus confrontos com outros metahumanos — em um site real, compreendendo na prática o peso e a importância da marcação semântica.

## Estrutura de Pastas e Páginas
A navegação foi estruturada como uma crônica contínua. O site conta com uma página matriz na raiz e 11 páginas secundárias de narrativa dentro da pasta `html/` (atualmente referenciada localmente como `pages/`):

- **`/index.html`** (Raiz) - Hub central de informações e sumário do projeto.
- **`html/01-rotina-em-dakota.html`** - A vida normal de Virgil no colégio.
- **`html/02-o-big-bang.html`** - A explosão do gás mutagênico "Quantum Juice" nas docas.
- **`html/03-despertar-eletrico.html`** - Os primeiros sinais de eletromagnetismo corporal.
- **`html/04-o-nascimento-do-heroi.html`** - Confecção do traje e equipamentos com a ajuda de Richie.
- **`html/05-primeira-patrulha.html`** - Testes de voo pelos prédios da cidade.
- **`html/06-os-bebes-do-big-bang.html`** - Banco de dados confidencial de outros mutantes.
- **`html/07-confronto-com-hotstreak.html`** - O primeiro grande duelo contra Francis Stone.
- **`html/08-vida-dupla-em-risco.html`** - O desafio da identidade secreta perante a família.
- **`html/09-batalha-eletromagnetica.html`** - Confronto que exigiu potência máxima.
- **`html/10-o-protetor-de-dakota.html`** - Conclusão do arco do herói.
- **`html/11-registro-metahumano.html`** - Sistema avançado de denúncias via formulário.

O projeto também consome mídia local das pastas de apoio (`img/`e `audio/`) para ilustrar os acontecimentos.

## Principais Tags e Semântica Utilizadas (100% HTML Puro)

- **Estruturação Semântica:** Uso massivo de `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>` e `<footer>`.
- **Formulários e Inputs Avançados:** A página de registro utiliza atributos que geram interfaces visuais automaticamente no navegador, como `<input type="date">`, `type="color"`, `type="range"`, `type="file"`, botões de `<button type="reset">` e o sistema de autocompletar da tag `<datalist>`.
- **Interatividade sem Scripts:** Criação de sanfonas de texto expansíveis usando `<details>` e `<summary>`.
- **Métricas Visuais:** Barras preenchidas utilizando `<meter>` (para capacidade estática) e `<progress>` (para calibração de itens).
- **Multimídia Nativa:** Incorporação de mídia local sem plug-ins através de `<audio controls>`, `<video controls>`, e estruturação imagética com `<figure>` e `<figcaption>`.
- **Marcações de Texto Avançadas:** Tags menos comuns mas de forte valor semântico como `<abbr>` (para siglas), `<mark>` (marca-texto), `<blockquote>` (citações diretas) e as tags `<del>`/`<ins>` para simular correção em documentos policiais.