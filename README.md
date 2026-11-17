# Tarefa 3.1 b) — Extensão do Back-Office Animalec (Sponsors & Experts)

> **Unidade Curricular:** Programação Web Avançada  
> **Tema:** Desenho e Desenvolvimento de Aplicações Web Responsivas (Front-End)  
> **Estudante:** Miguel Correia  
> **Número de Estudante:** 1103691  
> **Caso de Estudo:** Extensão da Área de Administração do Projeto Animalec (Capítulo A.3)  

---

## 📌 1. Enquadramento do Projeto

Esta prova de conceito estende as funcionalidades da plataforma pedagógica **Animalec** (Queirós & Portela, 2020), introduzindo a gestão completa de duas novas entidades estratégicas no **Back-Office (`/admin`)**:
1. **`sponsors` (Patrocinadores):** Entidades mecenas que financiam a preservação de espécies animais em perigo, organizadas por escalões de patrocínio (*Ouro*, *Prata* e *Bronze*).
2. **`experts` (Especialistas Científicos):** Investigadores e biólogos curadores responsáveis pela validação biológica e rigor pedagógico dos conteúdos.

O protótipo foi concebido com uma **estrutura estritamente semântica em HTML5** e lógica reativa baseada em **Vue.js 3**, garantindo uma experiência responsiva tanto em **Desktop (Browser)** como em dispositivos **Mobile**.

---

## 🛠️ 2. Tecnologias e Especificação Técnica

- **HTML5 Semântico:** Utilização estruturada de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<dialog>`, `<fieldset>`, `<legend>` e campos de formulário tipificados (`type="email"`, `type="url"`).
- **CSS3 Moderno:** Arquitetura com Flexbox, CSS Grid, variáveis nativas (`:root`), transições e design adaptativo.
- **Vue.js 3 (via CDN):** Gestão de estado reativo no cliente (`ref`, `computed`), renderização condicional (`v-if`, `v-for`) e simulação interativa de rotas da SPA.
- **FontAwesome 6 & Google Fonts (Inter):** Iconografia temática e tipografia alinhadas com a identidade visual do Animalec.

---

## 📱 3. Funcionalidades & Simulação de Viewports

O protótipo inclui uma barra de controlo superior que permite ao avaliador alternar instantaneamente entre dois modos de visualização:
1. **Modo Browser (Desktop):** Apresentação em grelha ampla com tabelas semânticas tabulares (`<table>`), filtros em linha e modais centralizados.
2. **Modo Mobile:** Transformação automática das tabelas em listas de cartões verticais (*stacked cards*), botões de toque com espaçamento ergonómico e visualização integrada em moldura de *smartphone*.

---

## 🚀 4. Como Executar Localmente

1. Clonar o repositório ou descompactar os ficheiros na máquina local.
2. Abrir o ficheiro `index.html` diretamente em qualquer navegador moderno (Chrome, Edge, Firefox, Safari).
3. Não requer instalação prévia de dependências ou servidores Node.js (execução instantânea via CDN).
