# 🚀 Landing Page - Clone Zoom (Header Dinâmico)

Uma interface moderna e responsiva inspirada na Landing Page do **Zoom**, desenvolvida com **HTML5, CSS3 puro e JavaScript Vanilla**. O grande destaque do projeto é o **cabeçalho inteligente (sticky/fixed header)** que altera dinamicamente sua cor, bordas, estilos de botões e a logomarca conforme a navegação da página.

---

## 📸 Demonstração das Funcionalidades

- **Topo com Fundo Escuro:** Header com fundo transparente, texto/links em branco e logo na versão clara.
- **Rolagem para Fundo Claro:** Ao rolar a página para a seção branca, o header assume fundo branco opaco, adiciona sombra suave, altera a cor dos links e troca a logo para a versão escura.
- **Borda Inferior Alinhada:** A linha divisória do menu acompanha a largura do container interno, mantendo um visual limpo de ponta a ponta.

---

## ✨ Funcionalidades Principais

* [x] **Hero Section com Degradê Duplo:** Combinação de `radial-gradient` e `linear-gradient` reproduzindo o brilho central do Zoom.
* [x] **Header Fixo Responsivo (`position: fixed`):** Cabeçalho mantido no topo durante toda a navegação.
* [x] **Troca Dinâmica de Tema via JavaScript:** Monitoramento do evento `window.scrollY` para adicionar a classe `.rolado`.
* [x] **Troca da Logomarca no Scroll:** Alteração do atributo `src` da imagem da logo para garantir contraste ideal.
* [x] **Efeitos de Hover Avançados:** Botões com cantos arredondados, transições suaves (`transition`) e feedbacks visuais ao passar o mouse.

---

## 🛠️ Tech Stack & Ferramentas

- **HTML5:** Estruturação semântica da página (`<header>`, `<nav>`, `<main>`, `<section>`).
- **CSS3:** 
  - Flexbox para alinhamentos e distribuições no cabeçalho.
  - Gradientes CSS (`linear-gradient` e `radial-gradient`).
  - Efeitos de transição (`transition`) e sombras (`box-shadow`).
- **JavaScript (Vanilla):** Manipulação do DOM em tempo de execução sem dependência de bibliotecas externas.
- **VS Code (Visual Studio Code):** Editor de código fonte e ambiente de versionamento.
- **Git & GitHub:** Versionamento de código e hospedagem do repositório integrados diretamente no VS Code.

---

## 💻 Publicação e Controle de Versão via VS Code

A integração, versionamento e publicação no **GitHub** foram realizados inteiramente através do **Visual Studio Code**, utilizando a interface gráfica de **Source Control (Controle do Fonte)** nativa da IDE:

1. **Inicialização:** Repositório Git inicializado diretamente no painel do VS Code.
2. **Commit:** Alterações e staging organizados via interface visual.
3. **Publish to GitHub:** Publicação direta do repositório para o GitHub com autenticação integrada, dispensando o uso do terminal para os comandos iniciais de `git push`.

---

## 📂 Estrutura de Pastas do Projeto

```text
├── css/
│   └── estilo.css          # Estilos globais e estados do header
├── img/
│   ├── logo-zoom-white.png # Logo para fundo escuro
│   └── logo.svg            # Logo para fundo claro
├── index.html              # Estrutura principal da aplicação
└── README.md               # Documentação do projeto
