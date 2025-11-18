# Landing Page – Guia BBQ Ponto Raro 🍖🔥  
Landing page oficial do e-book **“Denver Steak: O Segredo Escondido no Acém”**, criada para apresentar o produto, explicar o conceito da marca e direcionar o visitante para a compra com segurança, performance e foco em conversão.

Este repositório contém todo o código da página publicada no domínio oficial:  
➡️ https://bbqpontoraro.com.br

---

## 🧰 Tecnologias utilizadas
A página foi construída de forma **100% estática**, utilizando:

- **HTML5 semântico**
- **CSS3 puro**, com:
  - responsividade mobile-first  
  - tokens de design  
  - animações suaves  
  - layout performático  
- **JavaScript Vanilla**, para:
  - lazy-load do vídeo  
  - eventos de analytics  
  - banner avançado de consentimento (LGPD)  
- **Google Analytics 4** (via consentimento)
- **Microsoft Clarity** (via consentimento)
- **YouTube Privacy-Enhanced Mode** (youtube-nocookie)

---

## 🎯 Objetivo do projeto
O propósito desta landing page é servir como:

- ponto central de apresentação do e-book;
- página de vendas rápida, enxuta e leve;
- vitrine técnica para demonstrar conhecimento sobre:
  - experiência do usuário (UX),
  - boas práticas de SEO,
  - estruturação de HTML limpo,
  - acessibilidade,
  - otimização para performance,
  - integração responsável de rastreamento (consent mode).

O site está hospedado atualmente na **Netlify**.

---

## 🔍 Destaques técnicos

### ✔️ **Performance e otimização**
- imagens `.webp` otimizadas;
- preload de fontes;
- uso de `prefetch` e `preconnect`;
- carregamento condicional de scripts de Analytics e Clarity.

### ✔️ **Acessibilidade**
- navegação via teclado com `skip-link`;
- foco visível (`:focus-visible`);
- alt-text nas imagens;
- textos semânticos utilizando `<header>`, `<main>`, `<section>`, `<footer>`.

### ✔️ **LGPD e consentimento**
A página inclui um **banner de consentimento de cookies customizado**, com:

- “aceitar todos”
- “rejeitar não essenciais”
- modal avançado para configurações  
- cookies analíticos e funcionais bloqueados por padrão  
- carregamento apenas após consentimento explícito

### ✔️ **Comportamento do vídeo**
O player só carrega quando o usuário clica (lazy load), usando:

- placeholder otimizado
- botão de play com SVG/png
- embed com `youtube-nocookie`
