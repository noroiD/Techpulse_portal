# TechPulse - Portal de Notícias de Tecnologia

Projeto desenvolvido como primeira versão funcional da página inicial do portal **TechPulse**, aplicando rigorosamente a separação entre estrutura (HTML5 semântico) e apresentação (CSS3 externo), com foco em acessibilidade, organização de código e responsividade.

---

## Especificações Técnicas e Justificativas

### 1. Paleta de Cores (Hexadecimal e RGBA)
* **Azul Marinho Profundo (`#0f172a`):** Utilizado no cabeçalho e no rodapé para transmitir credibilidade, seriedade editorial e alto contraste com textos claros.
* **Cinza Claro (`#f1f5f9`) e Branco (`#ffffff`):** Aplicados no fundo da página e nos cartões de conteúdo para garantir conforto visual e leitura limpa sem fadiga ocular.
* **Azul Royal (`#2563eb` / `#3b82f6`):** Usado como cor de destaque em bordas e botões de ação (*Call to Action*), direcionando o olhar do leitor para elementos interativos.
* **Sombras e Transparências (`rgba(15, 23, 42, 0.08)` e `rgba(37, 99, 235, 0.85)`):** Empregadas para criar profundidade sutil nos cartões e feedback visual suave ao passar o cursor sobre o botão.

### 2. Tipografia
* **Família Tipográfica:** `'Segoe UI', Tahoma, Geneva, Verdana, sans-serif` — fontes sem serifa (*sans-serif*) modernas que oferecem excelente legibilidade em telas de computadores e dispositivos móveis.
* **Hierarquia e Escala:** Tamanho base de `16px` no corpo do texto com altura de linha (`line-height: 1.6`) para leitura fluida, títulos principais em `2.2rem` e subtítulos em `1.75rem`, ajustados proporcionalmente em telas menores via *Media Queries*.

### 3. Espaços Criados e Box Model
* **Cabeçalho (`#cabecalho-principal`):** Centraliza a identidade da marca e a barra de navegação (`<nav>`), delimitado por `padding` interno e uma borda inferior (`border-bottom`) de destaque.
* **Área Principal (`<main>`) e Artigo (`.destaque-noticia`):** Centralizados na tela com `margin: 32px auto` e largura máxima (`max-width: 850px`), utilizando `padding: 32px` e `border` para separar visualmente a reportagem do fundo da página.
* **Rodapé (`<footer>`):** Encerra a página com informações institucionais e de direitos autorais, separado do conteúdo principal por `margin-top: 40px`.

### 4. Tecnologias e Serviços Utilizados
* **HTML5 Semântico:** Uso de `<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`, listas estruturadas (`<ul>`) e atributos `alt` em imagens para SEO e compatibilidade com leitores de tela.
* **CSS3 Externo:** Separação completa de estilos via `<link>`, utilizando seletores de tag, ID (`#`), classe reutilizável (`.`), Box Model (`margin`, `border`, `padding`) e Design Responsivo (`@media`).

---

## Sitemap Visual (Arquitetura da Informação e Taxonomia)

A estrutura abaixo organiza a hierarquia de navegação do portal **TechPulse**, partindo da página inicial para três editorias principais e suas respectivas subcategorias:

```text
TechPulse (Página Inicial - Home)
│
├── 1. Inteligência Artificial
│   ├── 1.1 Machine Learning & Deep Learning
│   ├── 1.2 IA Generativa e LLMs
│   └── 1.3 Ética e Regulamentação
│
├── 2. Desenvolvimento Web
│   ├── 2.1 Front-end & UI/UX
│   ├── 2.2 Back-end & APIs
│   └── 2.3 Cloud Computing & DevOps
│
└── 3. Cibersegurança
    ├── 3.1 Segurança de Redes e Infraestrutura
    ├── 3.2 Privacidade e Proteção de Dados (LGPD)
    └── 3.3 Análise de Vulnerabilidades
```
