---

<div align="center">

```
██████╗  █████╗ ███████╗ █████╗ ███████╗██╗         ███████╗ █████╗ ███╗   ██╗ ██████╗ ██╗   ██╗██╗███╗   ██╗██╗
██╔══██╗██╔══██╗██╔════╝██╔══██╗██╔════╝██║         ██╔════╝██╔══██╗████╗  ██║██╔════╝ ██║   ██║██║████╗  ██║██║
██████╔╝███████║█████╗  ███████║█████╗  ██║         ███████╗███████║██╔██╗ ██║██║  ███╗██║   ██║██║██╔██╗ ██║██║
██╔══██╗██╔══██║██╔══╝  ██╔══██║██╔══╝  ██║         ╚════██║██╔══██║██║╚██╗██║██║   ██║██║   ██║██║██║╚██╗██║██║
██║  ██║██║  ██║██║     ██║  ██║███████╗███████╗    ███████║██║  ██║██║ ╚████║╚██████╔╝╚██████╔╝██║██║ ╚████║██║
╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝  ╚═╝╚══════╝╚══════╝    ╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝  ╚═════╝ ╚═╝╚═╝  ╚═══╝╚═╝
```

# Site de Portfolio


### Fullstack Developer · Computer Engineering Student · PUC-Campinas

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-555555?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-7C3AED?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JAVASCRIPT-555555?style=for-the-badge&logo=javascript&logoColor=white">
  <img src="https://img.shields.io/badge/PYTHON-7C3AED?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/C-555555?style=for-the-badge&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/ASSEMBLY-7C3AED?style=for-the-badge&logo=gnuemacs&logoColor=white">
  <img src="https://img.shields.io/badge/TYPESCRIPT-555555?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/REACT-7C3AED?style=for-the-badge&logo=react&logoColor=white">
  <img src="https://img.shields.io/badge/API-555555?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/FIGMA-7C3AED?style=for-the-badge&logo=figma&logoColor=white">
  <img src="https://img.shields.io/badge/GIT-555555?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/GITHUB-7C3AED?style=for-the-badge&logo=github&logoColor=white">
</p>


<br/>

[![Status](https://img.shields.io/badge/STATUS-LIVE-7C3AED?style=for-the-badge)](https://github.com/sanguinirafa76)
[![License](https://img.shields.io/badge/LICENSE-MIT-7C3AED?style=for-the-badge)](./LICENSE)
[![Open to Work](https://img.shields.io/badge/OPEN%20TO-INTERNSHIP/WORK-22C55E?style=for-the-badge)](mailto:rafaelcolagrossi@gmail.com)

<br/>

[Ver Portfolio](#) · [LinkedIn](https://linkedin.com/in/rafael-sanguini-b49ab11aa) · [GitHub](https://github.com/sanguinirafa76) · [Contato](mailto:rafaelcolagrossi@gmail.com)

<br/>
</div>

---

</div>

<br/>

## Visão Geral

> **Um portfólio que não e só uma página — e uma experiência.**

Desenvolvido com **HTML5 puro, CSS3 e JavaScript Vanilla**, esse portfólio foi construído do zero com foco em design moderno, animacoes fluidas e performance. Cada detalhe foi pensado para impressionar: do cursor customizado ao card flip interativo, dos orbs com parallax ao reveal animado das secoes.

Representa minha identidade como desenvolvedor **Fullstack** — alguém que domina tanto a camada visual quanto a lógica por trás dos sistemas.

<br/>

## Features

<table>
<tr>
<td width="50%">

**Parallax Orbs**
Tres orbs de fundo que respondem ao movimento do mouse em tempo real — profundidade sem biblioteca externa.

**Reveal on Scroll**
`IntersectionObserver` nativo para animacao de entrada staggered dos elementos conforme o usuario rola a pagina.

**Skill Bars Animadas**
Barras de habilidade que preenchem com animacao suave no momento em que entram no viewport.

</td>
<td width="50%">

**Card Flip Interativo**
Card 3D que exibe um editor de codigo na frente e a foto do desenvolvedor no verso, com transicao CSS pura.

**Glow Dinamico nos Cards**
Efeito de glow nos cards de projetos que segue o cursor do mouse com `radial-gradient` reativo.

**Modal de Perfil**
Modal animado com detalhes completos, acessivel via teclado com trap de foco e fechamento por `Escape`.

**Copy Email**
Botao para copiar o e-mail com feedback visual — compativel com `Clipboard API` e fallback para browsers antigos.

</td>
</tr>
</table>

<br/>

## Tech Stack

```javascript
const portfolio = {
  linguagens : ["HTML5", "CSS3", "JavaScript Vanilla"],
  tipografia  : ["Syne (display)", "DM Sans (body)"],
  icones      : ["Lucide Icons (unpkg CDN)"],
  animacoes   : ["CSS Animations", "IntersectionObserver", "requestAnimationFrame"],
  hospedagem  : "Vercel / GitHub Pages",
  bundler     : null,   // zero dependencias de build
  frameworks  : null,   // puro e performatico
};
```

> **Zero frameworks. Zero build tools. Zero tempo de setup.** Abre o `index.html` e funciona.

<br/>

## Estrutura do Projeto

```
portfolio_sanguinirafa/
│
├── index.html              # Pagina principal — toda a estrutura semantica
│
├── css/
│   └── style.css           # ~45KB de CSS — design system, animacoes, responsividade
│
├── js/
│   └── main.js             # Toda a interatividade: cursor, modal, scroll, reveal
│
└── imagens/
    ├── fotominha1.jpg       # Foto do perfil (modal + secao About)
    ├── fotominha2.jpeg      # Foto principal (hero)
    ├── fotominha7.jpeg      # Foto no card flip (secao Skills)
    ├── StarzUp! - Projeto.jpeg
    ├── InvestX - Projeto.jpeg
    ├── Login_Cadastro - projeto.jpeg
    ├── Jogo da Velha - Projeto.jpeg
    └── [logos e icones sociais]
```

<br/>

## Secoes

| # | Secao | Destaque Tecnico |
|---|-------|-----------------|
| 1 | **Hero** | Grid layout com foto + floating badges, orbs com parallax, stats animados |
| 2 | **Sobre** | Layout two-column, foto circular com spin-ring CSS, modal de perfil completo |
| 3 | **Projetos** | Cards com glow reativo, mockup de browser embutido, expand/collapse animado |
| 4 | **Skills** | Barras animadas por IntersectionObserver, card flip 3D com editor de codigo |
| 5 | **Contato** | Copia de e-mail com feedback, cards de canal clicaveis, links sociais |
| 6 | **Footer** | Grid responsivo com navegacao, contato e branding |

<br/>

## Projetos em Destaque

### 01 · [Starz Up!](https://github.com/RaphaelSalesDEV/Starz-Up)
> Plataforma semiprofissional de **E-sports** para organizacao de campeonatos de jogos digitais.

![HTML5](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

Layout responsivo, logica de estruturacao de torneios e integracao com Firebase para persistencia de dados.

---

### 02 · [InvestX](https://github.com/sanguinirafa76/InvestX)
> Suporte a **decisoes financeiras com IA integrada**, foco em usabilidade e performance.

![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![AI](https://img.shields.io/badge/AI-7C3AED?style=flat-square)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![APIs](https://img.shields.io/badge/REST%20APIs-22C55E?style=flat-square)

Interface focada em analise de investimentos com inteligencia artificial e consumo de APIs financeiras em tempo real.

---

### 03 · [Cadastro & Login Fullstack](https://github.com/sanguinirafa76/Pagina-de-cadastro-login)
> Sistema completo de **autenticacao com JWT** e gerenciamento de sessoes.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

Autenticacao segura com tokens JWT, protecao de rotas e interface moderna. Projeto fullstack completo.

---

### 04 · [Jogo da Velha · Assembly](https://github.com/sanguinirafa76/Jogo_da_velha-)
> Jogo classico implementado em **Assembly** — controle de fluxo de baixo nivel.

![Assembly](https://img.shields.io/badge/Assembly-6E4C13?style=flat-square)
![Low-Level](https://img.shields.io/badge/Low%20Level-EF4444?style=flat-square)

Demonstracao de dominio em programacao de baixo nivel: logica do jogo, controle de fluxo e manipulacao direta de registradores.

<br/>

## Como Rodar Localmente

Nao precisa de nada instalado.

```bash
# 1. Clone o repositorio
git clone https://github.com/sanguinirafa76/portfolio.git

# 2. Entre na pasta
cd portfolio

# 3. Abra no navegador
open index.html
```

**Opcional — servidor local com Live Reload:**

```bash
# Com VS Code + extensao Live Server
# Clique com botao direito em index.html -> "Open with Live Server"

# Ou com Python:
python -m http.server 3000
# Acesse: http://localhost:3000
```

<br/>

## Responsividade

O portfolio e **100% responsivo** e funciona em todos os dispositivos:

| Dispositivo | Breakpoint | Comportamento |
|-------------|-----------|---------------|
| Mobile   | `< 768px` | Menu hamburger, layout single-column, cursor desativado |
| Tablet   | `768–1024px` | Layout adaptado, grid simplificado |
| Desktop | `> 1024px` | Cursor customizado, parallax ativo, layout full |

<br/>

## Acessibilidade

- Atributos `aria-label` em todos os elementos interativos
- Navegacao completa por teclado (`Tab`, `Enter`, `Escape`)
- Trap de foco no modal
- `aria-expanded` dinamico no hamburger e botao de projetos
- `aria-hidden` em cards ocultos
- `aria-live="polite"` no toast de copia de e-mail
- Semantica HTML5 correta (`nav`, `section`, `article`, `footer`)

<br/>

## Skills

```
Frontend
  JavaScript  ██████████████████░░  90%
  TypeScript  ████████████████░░░░  80%
  React       ███████████████░░░░░  75%
  HTML5/CSS3  ███████████████████░  95%

Backend & Linguagens
  Python      ███████████████░░░░░  75%
  C           █████████████░░░░░░░  65%
  Assembly    ███████████░░░░░░░░░  55%
  APIs REST   ████████████████░░░░  80%

Ferramentas
  Git/GitHub  █████████████████░░░  85%
  Firebase    ████████████████░░░░  80%
  Figma       ██████████████░░░░░░  70%

Idiomas
  Portugues   ████████████████████  100%  (Nativo)
  Ingles      ███████████████████░  95%   (Avancado)
  Espanhol    █████████████░░░░░░░  65%   (Intermediario)
  Italiano    ████░░░░░░░░░░░░░░░░  20%   (Basico)
```

<br/>

## Contato

<div align="center">

| Canal | Info |
|-------|------|
| Email | [rafaelcolagrossi@gmail.com](mailto:rafaelcolagrossi@gmail.com) |
| LinkedIn | [rafael-sanguini](https://linkedin.com/in/rafael-sanguini-b49ab11aa) |
| GitHub | [@sanguinirafa76](https://github.com/sanguinirafa76) |
| WhatsApp | [+55 (11) 98236-0707](https://wa.me/5511982360707?text=Ola%20Rafael!%20Acabei%20de%20analisar%20seu%20portfolio%20e%20me%20interessei%20pelo%20seu%20trabalho.) |
| Localizacao | Jundiai, Sao Paulo · Brasil |

</div>

<br/>

---

<div align="center">

**Disponível para estágio em desenvolvimento Fullstack**

Desenvolvido por **Rafael Sanguini Colagrossi**
Estudante de Engenharia da Computacao · PUC-Campinas · 3 Semestre

<br/>

*"Transformando ideias em experiencias digitais memoráveis."*

<br/>

© 2026 Rafael Sanguini. Todos os direitos reservados.

</div>
