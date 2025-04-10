
# 🚀 Desafio 3 - Deploy Automatizado de Aplicação Estática no GitHub Pages

Este projeto é parte de um desafio prático que tem como objetivo configurar um fluxo de CI/CD usando **GitHub Actions** para publicar automaticamente um site estático no **GitHub Pages**.

---

## 📄 Descrição

Criamos um site simples com HTML, CSS e JavaScript, e configuramos um workflow no GitHub Actions para:

- Executar em cada `push` para a branch `main`
- Fazer o deploy automático do conteúdo para o GitHub Pages

---

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- GitHub Actions
- GitHub Pages

---

## ⚙️ Estrutura do Projeto

```bash
📁 projeto/
├── index.html
├── style.css
├── script.js
└── .github/
    └── workflows/
        └── deploy.yml
```

---

## 🚀 Como executar

1. Faça um clone do repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

2. Suba o código para a branch `main`:

```bash
git add .
git commit -m "Deploy inicial"
git push -u origin main
```

3. Vá até o repositório no GitHub:
- Acesse **Settings > Pages**
- Selecione **"GitHub Actions"** como source
- Pronto! O site será publicado automaticamente após cada `push`.

