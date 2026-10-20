# Rafael Sanguini — Portfólio Pessoal

> **Este portfólio é um projeto em constante evolução.** Ele cresce junto comigo — cada nova habilidade, projeto e conquista da minha carreira é refletida aqui. O que você vê hoje é um retrato da minha trajetória, não um produto finalizado.

Um site de portfólio pessoal moderno, com tema escuro, desenvolvido com HTML, CSS e JavaScript puro. Sem frameworks, sem ferramentas de build — apenas código limpo e semântico.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Projeto%20em%20Evolu%C3%A7%C3%A3o-blueviolet?style=flat-square)

---

##  Visão geral

Este não é um portfólio estático. É uma **representação em constante evolução da minha carreira**, atualizada continuamente conforme aprendo novas tecnologias, desenvolvo projetos, alcanço novos objetivos e evoluo como desenvolvedor.

Cada seção foi projetada para evoluir:

- **Projetos** serão adicionados conforme forem desenvolvidos.
- **Habilidades** serão ampliadas à medida que eu aprender novas tecnologias.
- **Experiência** será atualizada conforme eu avançar profissionalmente.
- **Design** poderá evoluir à medida que meu senso estético se aperfeiçoar.

Desenvolvido do zero como meu primeiro projeto de portfólio, com foco em código limpo, acessibilidade e práticas modernas de UI/UX, sem depender de frameworks de front-end.

---

##  Funcionalidades

### Interface e experiência do usuário (UI/UX)

- **Design em modo escuro** com paleta de cores e detalhes em roxo.
- **Totalmente responsivo**, com seis breakpoints, de dispositivos móveis a desktops.
- **Rolagem suave** na navegação, com acompanhamento do link ativo.
- **Animações ao rolar a página**, implementadas com `IntersectionObserver`.
- **Efeito de esferas com parallax** em desktops, controlado pelo movimento do mouse.
- **Iluminação dinâmica nos cards de projetos**, com gradiente radial que acompanha o cursor.

### Navegação

- **Barra de navegação fixa** com comportamento dinâmico durante a rolagem.
- **Menu hambúrguer** para dispositivos móveis, com gerenciamento de foco.
- **Destaque automático da seção ativa**, de acordo com a posição da rolagem.

### Seções

- **Início (Hero)** — nome, biografia, estatísticas e botões de ação.
- **Sobre mim** — trajetória pessoal, formação acadêmica, idiomas e habilidades interpessoais.
- **Projetos** — cards em destaque com tecnologias utilizadas, links para o GitHub e visualização expansível.
- **Habilidades** — tecnologias organizadas por categorias, barras de progresso animadas e trecho de código.
- **Contato** — e-mail, WhatsApp e redes sociais, com funcionalidade de copiar informações.

### Interações

- **Botão para copiar e-mail**, com notificação visual (*toast*) e uso da Clipboard API com alternativa de compatibilidade.
- **Janela modal de perfil**, com contenção de foco e navegação pelo teclado, incluindo fechamento pela tecla `Escape`.
- **Barras de habilidades animadas**, ativadas quando entram na área visível da tela.
- **Ícones Lucide**, renderizados dinamicamente.

---

##  Tecnologias utilizadas

| Camada | Tecnologia |
|--------|------------|
| **Marcação** | HTML5 semântico |
| **Estilização** | CSS3 (propriedades personalizadas, Flexbox, Grid e `clamp()`) |
| **Lógica** | JavaScript puro (ES6+) |
| **Ícones** | Lucide Icons |
| **Hospedagem** | Vercel |
| **Controle de versão** | Git e GitHub |

---

##  Como começar

### Acesse o projeto on-line

O portfólio está hospedado na Vercel:

🔗 **[rafaelsanguini.vercel.app](https://rafaelsanguini.vercel.app)**

### Execute localmente

1. Clone o repositório:

```bash
git clone https://github.com/rsanguini/portfolio.git
cd portfolio
```

2. Abra o arquivo `index.html` em qualquer navegador moderno. Não é necessário executar um processo de build, instalar dependências ou iniciar um servidor.

---

##  Arquitetura

```text
portfolio/
├── css/
│   └── style.css          # Estilos, propriedades personalizadas, responsividade e animações
├── js/
│   └── main.js            # Interações: navegação, rolagem, modal, área de transferência e animações
├── assets/
│   ├── photos/            # Fotos pessoais: início, sobre mim e habilidades
│   ├── projects/          # Miniaturas e capturas de tela dos projetos
│   └── icons/             # Ícones de redes sociais e da interface
├── index.html             # Estrutura da página única
├── .gitignore             # Exclusões de sistema operacional, editor e arquivos de ambiente
├── LICENSE                # Licença MIT
└── README.md              # Este arquivo
```

### Detalhes importantes da implementação

| Funcionalidade | Implementação |
|----------------|---------------|
| **Design responsivo** | Media queries CSS com seis breakpoints, de 320 px a 1440 px ou mais |
| **Tipografia fluida** | `clamp()` do CSS para dimensionamento escalável das fontes |
| **Animações de rolagem** | `IntersectionObserver` com atrasos escalonados |
| **Área de transferência** | API `navigator.clipboard`, com alternativa usando `execCommand` |
| **Acessibilidade do modal** | Contenção de foco, `aria-expanded`, tecla `Escape` e restauração do foco |
| **Menu para dispositivos móveis** | Bloqueio da rolagem do corpo da página, fechamento ao clicar fora e `aria-expanded` |
| **Desempenho** | Ausência de frameworks externos de CSS e JavaScript, com arquivos únicos e sobrecarga mínima |
| **Sistema de cores** | Propriedades personalizadas do CSS, como `--accent`, `--bg` e `--card` |

---

##  Breakpoints responsivos

| Breakpoint | Dispositivo-alvo |
|------------|------------------|
| `≤ 480px` | Celulares pequenos |
| `≤ 600px` | Celulares convencionais |
| `≤ 768px` | Celulares grandes e tablets pequenos |
| `≤ 900px` | Tablets |
| `≤ 1200px` | Notebooks pequenos |
| `> 1200px` | Desktops |

---

##  Roteiro de desenvolvimento

Este portfólio é um **projeto em constante evolução**. O roteiro abaixo representa o que já foi realizado e o que está planejado para acompanhar o desenvolvimento da minha carreira.

| Etapa | Descrição | Status |
|-------|-----------|--------|
| **1. Estrutura principal** | Início, Sobre mim, Projetos, Habilidades e Contato | ✅ Concluído |
| **2. Interações** | Animações de rolagem, modal, área de transferência e menu móvel | ✅ Concluído |
| **3. Responsividade** | Adaptação completa de dispositivos móveis a desktops | ✅ Concluído |
| **4. Publicação** | Hospedagem na Vercel com domínio personalizado | ✅ Concluído |
| **5. Expansão dos projetos** | Adicionar novos projetos conforme forem desenvolvidos | 🔄 Em andamento |
| **6. Expansão das habilidades** | Atualizar as barras de habilidades conforme novas tecnologias forem aprendidas | 🔄 Em andamento |
| **7. Seção de artigos** | Escrever sobre aprendizados, projetos e trajetória profissional | 🔜 Planejado |
| **8. Alternância entre temas** | Alternar entre os modos claro e escuro conforme a preferência do usuário | 🔜 Planejado |
| **9. Internacionalização (i18n)** | Suporte a múltiplos idiomas (português e inglês) | 🔜 Planejado |
| **10. Filtros de projetos** | Filtrar projetos por tecnologia, categoria ou ano | 🔜 Planejado |

> **Observação:** as etapas 5 e 6 permanecem intencionalmente em andamento, pois este portfólio foi projetado para crescer comigo. Conforme aprendo novas tecnologias, concluo projetos ou alcanço objetivos profissionais, este repositório e o site publicado serão atualizados para refletir esse progresso.

---

##  Autor

**Rafael Sanguini Colagrossi** 
-- Desenvolvedor de software apaixonado por Códigos, Inteligência Artificial, Tecnologia e Desenvolvimento Full-Stack.

Criando softwares modernos com foco em desempenho, arquitetura limpa e excelente experiência do usuário. --

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafaelsanguini)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rsanguini)
[![E-mail](https://img.shields.io/badge/E--mail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rafaelcolagrossi@gmail.com)

---

## Licença

Este projeto está licenciado sob a **Licença MIT**. Consulte o arquivo [LICENSE](LICENSE) para obter mais informações.

---

⭐ Se este projeto foi útil para você, deixe uma estrela no repositório — isso significa muito!
