# Entrega 2 – Estilização e Leiautes (HTML5 + CSS3)

Projeto desenvolvido como parte da **Entrega 2** da disciplina **Fundamentos e Estruturação de Sistemas**, com foco na aplicação prática de **CSS3** para criar uma interface profissional, moderna e responsiva a partir da estrutura HTML da Entrega I.

---

## Objetivos do Projeto

- Aplicar **conceitos de Design System** com variáveis CSS customizadas.  
- Utilizar **Flexbox e Grid** para construção de leiautes modernos e responsivos.  
- Implementar **componentes interativos** (menu, cards, botões, formulários).  
- Garantir **acessibilidade, responsividade e consistência visual** entre todas as páginas.  

---

## 🧱 Estrutura do Projeto

Entrega2-estilizacao/
├─ index.html
├─ projetos.html
├─ cadastro.html
├─ css/
│  ├─ base.css
│  ├─ layout.css
│  ├─ components.css
│  └─ styles.css
├─ js/
│  └─ masks.js
├─ images/
│  ├─ logo.png
│  ├─ hero.jpg
│  ├─ projeto1.jpg
│  ├─ projeto2.jpg
│  └─ projeto3.jpg
└─ README.md

---

## Design System

### Paleta de Cores
- Primárias: `--color-primary`, `--color-primary-light`, `--color-primary-dark`  
- Secundárias: `--color-secondary`, `--color-secondary-dark`  
- Neutras: `--color-neutral-100`, `--color-neutral-200`, `--color-neutral-400`, `--color-neutral-800`

### Tipografia
- Hierarquia de 5 tamanhos:  
  `--font-size-xxl`, `--font-size-xl`, `--font-size-lg`, `--font-size-md`, `--font-size-sm`

### Sistema de Espaçamento
- Modular: `8px, 16px, 24px, 32px, 48px, 64px`  
- Raio padrão de borda: `8px`

---

## Componentes e Funcionalidades

**Menu principal** com submenu dropdown e menu hambúrguer no mobile  
**Cards de projetos** responsivos com badges/tags de categoria  
**Botões interativos** com estados `hover`, `active`, `disabled`  
**Formulários estilizados**, com validação visual (`:valid` / `:invalid`)  
**Feedbacks de interface**: alert, toast e modal animado  
**Leiaute 100% responsivo** (Grid 12 colunas + Flexbox)  
**5 breakpoints definidos** (1200px, 992px, 768px, 576px, 400px)

---

## Páginas

| Página | Descrição |
|--------|------------|
| **index.html** | Página inicial com banner e informações gerais da organização |
| **projetos.html** | Mostra os projetos sociais com cards e tags de categoria |
| **cadastro.html** | Formulário de voluntariado com máscaras, validação e modal de confirmação |

---

## Tecnologias Utilizadas

- HTML5  
- CSS3 (Flexbox, Grid e Variáveis)  
- JavaScript (Vanilla)  
- Validação nativa e máscaras com JS  
- GitHub Pages para publicação

---

## Publicação

**Repositório Público:**  
[https://github.com/ismaelgpereira/Entrega2-estilizacao](https://github.com/ismaelgpereira/Entrega2-estilizacao)

**Site Publicado (GitHub Pages):**  
[https://ismaelgpereira.github.io/Entrega2-estilizacao/](https://ismaelgpereira.github.io/Entrega2-estilizacao/)

---

## Autor

**Nome:** Ismael Gomes Pereira  
**Curso:** Análise e Desenvolvimento de Sistemas  
**Atividade:** Entrega II – Estilização e Layouts  
**Data:** Outubro / 2025  

---

## ✅ Validação W3C

Todos os arquivos HTML foram testados e validados no  
[W3C Validator](https://validator.w3.org/) garantindo conformidade com os padrões HTML5.
