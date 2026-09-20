# 🐾 DogPedia

Projeto final da Unidade I de HTML — uma enciclopédia sobre raças de cães, desenvolvida como trabalho acadêmico com foco 100% em HTML semântico (sem uso de CSS ou JavaScript).

**Desenvolvido por:** Arthur Oliveira Silva

---

## 📖 Sobre o projeto

O DogPedia é um site informativo dedicado ao universo canino, reunindo conteúdo sobre diferentes raças de cães, cuidados, alimentação, curiosidades e um formulário de interesse em adoção. O objetivo do projeto é aplicar na prática os principais conceitos de HTML aprendidos em aula: estruturação semântica, multimídia, formulários avançados, elementos interativos e marcação avançada de texto.

---

## 🗂️ Estrutura de pastas

```
Projeto final HTML/
├── Html/       → todas as páginas .html do site
├── Img/        → imagens usadas no projeto (logo, raças, destaque)
├── audio/      → arquivos de áudio (latidos)
├── video/      → arquivos de vídeo locais (raças em ação)
└── README.md   → este arquivo
```

---

## 📄 Páginas do site

| Página | Descrição |
|---|---|
| `index.html` | Página inicial, com boas-vindas e imagem de destaque |
| `sobre.html` | Sobre o projeto e seu propósito acadêmico |
| `racas.html` | Página "hub" com miniaturas clicáveis das 5 raças |
| `raca-pastoralemao.html` | Ficha completa do Pastor Alemão |
| `raca-labrador.html` | Ficha completa do Labrador |
| `raca-bulldog.html` | Ficha completa do Bulldog Inglês |
| `raca-poodle.html` | Ficha completa do Poodle |
| `raca-viralata.html` | Ficha completa do SRD (Vira-lata) |
| `cuidados.html` | Dicas gerais de cuidados, tabela e vídeo incorporado |
| `alimentacao.html` | Dicas de alimentação e tabela de porções |
| `adocao.html` | Formulário avançado de interesse em adoção |
| `faq.html` | Perguntas frequentes em formato expansível |
| `contato.html` | Formulário de contato + mapa de localização |

**Total: 13 páginas HTML**, todas interligadas por um menu de navegação (`<nav>`) presente em 100% do site.

---

## 🏗️ Tags semânticas utilizadas

Todas as páginas seguem a mesma estrutura semântica:

- `<header>` — identificação do site (logo, título, subtítulo)
- `<nav>` — menu de navegação, igual em todas as páginas
- `<main>` — conteúdo principal e único de cada página
- `<section>` — blocos temáticos de conteúdo
- `<article>` — usado no FAQ, onde cada pergunta/resposta é um conteúdo independente
- `<aside>` — usado na página de Contato, com formas alternativas de contato e mapa
- `<footer>` — direitos autorais e informações de rodapé

---

## 🎬 Multimídia

- **Áudio:** cada página de raça possui um `<audio>` com o latido característico
- **Vídeo:** cada página de raça possui um `<video>` local com controls
- **Imagem com `<figure>`/`<figcaption>`:** presente na home, na página de raças (miniaturas) e em cada ficha de raça
- **`<iframe>`:** vídeo do YouTube com dicas de cuidados (`cuidados.html`) e mapa do Google Maps (`contato.html`)

---

## 📝 Formulários

**`adocao.html`** — formulário avançado com:
- `type="date"` (data de nascimento)
- `type="file"` (foto da residência)
- `type="range"` (porte de cão desejado)
- `type="color"` (cor da coleira)
- `<datalist>` com sugestões das raças do site
- Campos com `required` e `placeholder`

**`contato.html`** — formulário simples de contato, também com `required` e `placeholder`

---

## 🧩 Elementos interativos

- `<details>` e `<summary>` — usados nas fichas de raça (curiosidades) e no FAQ (perguntas expansíveis)

---

## ✨ Marcação avançada de texto

Utilizadas ao longo das páginas de raça, cuidados e alimentação:

- `<mark>` — destaque de informações importantes
- `<abbr>` — siglas com significado (ex: CBKC)
- `<blockquote>` — citações sobre as raças
- `<cite>` — fonte das citações
- `<del>` e `<ins>` — comparações de mito x verdade
- `<progress>` — indicadores de progresso (alimentação)
- `<meter>` — medições de nível de energia e adestramento por raça

---

## ⚠️ Observações

- Projeto desenvolvido exclusivamente com HTML, sem uso de CSS ou JavaScript, conforme exigido pelo enunciado.
- Todas as imagens, áudios e vídeos utilizados são de bancos gratuitos (Pixabay, Unsplash, entre outros) ou gerados por IA, usados exclusivamente para fins educacionais.
- O site não possui backend, portanto os formulários não enviam dados de fato — sua função é demonstrar a estrutura e os atributos de formulários em HTML.
