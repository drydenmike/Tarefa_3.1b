# Tarefa 3.1 b) - Extensão do Back-Office Animalec (Sponsors & Experts)

> **Unidade Curricular:** Programação Web Avançada  
> **Tema:** Desenho e Desenvolvimento de Aplicações Web Responsivas (Front-End)  
> **Estudante:** Miguel Correia  
> **Número de Estudante:** 1103691  
> **Caso de Estudo:** Extensão da Área de Administração do Projeto Animalec (Capítulo A.3)  
> **Repositório Git Autónomo:** `Tarefa_3.1b`  

---

## 📌 1. Enquadramento do Projeto

Esta prova de conceito estende as funcionalidades da plataforma pedagógica **Animalec** (Queirós & Portela, 2020), introduzindo a gestão completa de duas novas entidades estratégicas no **Back-Office (`/admin`)**:
1. **`sponsors` (Patrocinadores):** Entidades mecenas que financiam a preservação de espécies animais em perigo, organizadas por escalões de patrocínio (*Ouro*, *Prata* e *Bronze*).
2. **`experts` (Especialistas Científicos):** Investigadores, biólogos e curadores taxonómicos responsáveis pela validação biológica e rigor pedagógico dos conteúdos.

O protótipo foi concebido com uma **estrutura estritamente semântica em HTML5** e lógica reativa baseada em **Vue.js 3**, garantindo uma experiência responsiva tanto em **Desktop (Browser)** como em dispositivos **Mobile**.

---

## 🛠️ 2. Tecnologias e Especificação Técnica

- **HTML5 Semântico:** Utilização estruturada de elementos de marco (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`), janelas modais nativas (`<dialog>`), agrupamento de campos (`<fieldset>`, `<legend>`) e formulários com validação nativa de tipos (`type="email"`, `type="url"`, `required`).
- **CSS3 Moderno:** Arquitetura limpa com Flexbox, CSS Grid, variáveis nativas (`:root`), sticky footer dinâmico e design adaptativo para mobile.
- **Vue.js 3 (via CDN):** Gestão de estado reativo no cliente (`ref`, `computed`), renderização condicional (`v-if`, `v-for`), pesquisa e filtros em tempo real, e persistência reativa em memória.
- **FontAwesome 6 & Google Fonts (Inter):** Iconografia temática e tipografia alinhadas com a identidade visual do Animalec.

---

## 🚀 3. Funcionalidades Implementadas (Ciclo CRUD & Acesso Seguro)

1. **Acesso Seguro por Palavra-Passe (Capítulo A.3):**
   - Simulação de barreira de autenticação do administrador com login/password (`admin` / `admin123`).
   - Botão de encerramento de sessão na barra de navegação ("Terminar Sessão") para teste imediato do ecrã de bloqueio e desbloqueio.
2. **Ciclo CRUD Completo nas Novas Entidades:**
   - **Create (Adicionar):** Botão "+ Novo" com abertura de modal semântico e validação de campos obrigatórios.
   - **Read (Listar e Visualizar):** Tabela estruturada para Desktop, cartões tácteis para Mobile, e modal de detalhe rápido (`<dialog>`).
   - **Update (Editar):** Ação contextual com ícone de edição (lápis) que pré-preenche o formulário com os dados existentes e guarda as alterações reativamente na lista.
   - **Delete (Remover):** Exclusão dinâmica do registo com confirmação e emissão de notificação *toast*.
3. **Simulador de Viewport Integrado:**
   - Barra superior que permite alternar instantaneamente entre a vista **Browser (Desktop)** (tabelas e grelha ampla) e **Mobile** (moldura de smartphone com cartões verticais empilhados).

---

## 💻 4. Como Executar Localmente

1. Clonar o repositório ou descarregar os ficheiros.
2. Abrir o ficheiro `index.html` diretamente em qualquer navegador moderno (Chrome, Edge, Firefox, Safari).
3. Não requer instalação prévia de dependências ou servidores Node.js (execução instantânea via CDN).
