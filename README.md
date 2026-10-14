# Brasa Alta — Landing Page

Landing page demonstrativa para uma hamburgueria artesanal fictícia, desenvolvida com HTML, CSS e JavaScript puros. O projeto foi pensado para portfólio e como base adaptável para pequenos negócios.

> **Aviso:** Brasa Alta é uma marca fictícia. Nome, endereço, preços, produtos, horários, depoimentos e contatos são apenas conteúdo demonstrativo.

## Objetivo

Apresentar a marca e os produtos com personalidade e conduzir o visitante até o pedido pelo WhatsApp. A experiência é mobile-first, acessível e não depende de frameworks ou processo de build.

## Tecnologias

- HTML5 semântico
- CSS3 organizado em tokens, reset, componentes, seções e responsividade
- JavaScript progressivo para menu móvel e pequenos comportamentos
- Imagens locais geradas especificamente para o conceito visual

## Como executar

Abra `index.html` diretamente no navegador ou, de preferência, rode um servidor local:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Personalização rápida

- **Cores e medidas:** `css/variables.css`
- **Nome e textos:** `index.html`
- **WhatsApp:** pesquise por `5511999999999` em `index.html`
- **Endereço, horários e redes:** seção `#visite` e rodapé em `index.html`
- **Produtos:** cards na seção `#cardapio`
- **Imagens:** substitua os arquivos em `assets/images/`, preservando nomes e proporções, ou atualize os caminhos no HTML
- **Metadados e favicon:** `<head>` de `index.html` e `assets/icons/favicon.svg`
- **Ordem das seções:** mova os blocos semânticos dentro de `<main>`; os estilos são isolados por seção

## Estrutura

```text
template-hamburgueria/
├── index.html
├── README.md
├── assets/
│   ├── fonts/
│   ├── icons/favicon.svg
│   └── images/
├── css/
│   ├── variables.css
│   ├── reset.css
│   ├── components.css
│   ├── sections.css
│   ├── responsive.css
│   └── style.css
└── js/main.js
```

## Acessibilidade e performance

- Link para pular ao conteúdo
- Menu móvel com estado e rótulo acessíveis
- Navegação por teclado e fechamento com `Esc`
- Foco visível e alvos de toque confortáveis
- Contraste consistente e conteúdo sem dependência de `hover`
- Respeito a `prefers-reduced-motion`
- Dimensões explícitas nas imagens para reduzir layout shift
- Lazy loading fora do hero e JavaScript mínimo

## Antes de usar comercialmente

Troque todo conteúdo fictício, confirme os valores e horários, adicione endereço real, configure o número oficial de WhatsApp e revise os textos legais. Comprima novamente as imagens conforme o formato usado na hospedagem.
