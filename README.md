# 🎤 Zingen — Landing Page

Landing page responsiva de um app de karaokê com Inteligência Artificial, desenvolvida como projeto de estudo durante a formação Front-End na [Rocketseat](https://rocketseat.com.br/).

---

## 🖥️ Preview

<img width="495" height="877" alt="image" src="https://github.com/user-attachments/assets/a828479f-a655-4a6c-8463-5ad7c6f23328" />


---

## 🔗 Deploy

Acesse o projeto online: **[https://zinge-karaoke.vercel.app/]**

---

## 📋 Sobre o projeto

O Zingen é um app fictício de karaokê que usa IA para remover a voz original de qualquer música, deixando-a pronta para cantar. A landing page foi construída do zero a partir de um layout no Figma, com foco em fidelidade ao design, responsividade e boas práticas de CSS.

### Seções da página

- **Header** — navegação fixa com links e botão de download
- **Hero** — chamada principal com ilustração e botões de ação
- **Sobre o app** — apresentação das funcionalidades principais
- **Features** — cards com layout em grid assimétrico
- **Planos e preços** — três planos com destaque para o plano Premium
- **Download** — CTA final com links para App Store e Play Store
- **Footer** — links institucionais e ícones de redes sociais com hover animado

---

## 🛠️ Tecnologias

- **HTML5** semântico
- **CSS3** puro — sem frameworks

---

## ✨ Conceitos praticados

- **CSS Modular** — arquivos separados por seção (`header.css`, `hero.css`, `footer.css`...)
- **CSS Nesting** nativo (sem pré-processador)
- **Custom Properties** (variáveis CSS) para cores, tipografia e espaçamentos
- **CSS Grid** para layouts complexos e assimétricos
- **Flexbox** para alinhamentos e navegação
- **Design responsivo mobile-first** com media queries
- **Acessibilidade** com `aria-label` em elementos interativos
- **Pseudo-elementos** (`::before`, `::after`) para efeitos visuais nos botões

---

## 📁 Estrutura de arquivos

```
zingen/
├── index.html
├── assets/
│   ├── icons/
│   └── ...imagens e SVGs
└── styles/
    ├── index.css       # importa todos os arquivos
    ├── global.css      # reset e variáveis
    ├── utility.css     # classes utilitárias
    ├── buttons.css
    ├── social.css
    ├── header.css
    ├── hero.css
    ├── sections.css
    ├── about.css
    ├── cards.css
    ├── features.css
    ├── pricing.css
    ├── download.css
    └── footer.css
```

---

## 🚀 Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/zingen.git

# Entre na pasta
cd zingen

# Abra o index.html no navegador
# (ou use a extensão Live Server no VS Code)
```

---

## 👨‍💻 Autor

Feito por **Leonardo** — estudante de Análise e Desenvolvimento de Sistemas em transição para Front-End.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leolfc/)
