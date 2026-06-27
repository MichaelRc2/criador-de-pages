# 🚀 Criador de Landing Pages com IA

Projeto que gera landing pages completas automaticamente utilizando inteligência artificial.


---

## 🧠 Sobre o projeto

Este projeto permite que o usuário descreva um negócio e, com base nisso, a aplicação gera automaticamente uma landing page completa com HTML e CSS.

A aplicação utiliza uma API de IA integrada de forma segura através de funções serverless.

---

## 🛠️ Tecnologias utilizadas

- HTML
- CSS
- JavaScript
- API de IA (Groq)
---

## 🔐 Segurança

Por segurança, a chave da API **não está exposta no frontend**.

A aplicação utiliza uma função backend para fazer as requisições, protegendo as credenciais com variáveis de ambiente.

---

## 📥 Como rodar o projeto localmente

### 1. Clone o repositório

```bash
git clone https://github.com/MichaelRc2/criador-de-pages.git
```

---

### 2. Acesse a pasta do projeto

```bash
cd criador-de-pages
```

---

### 3. Crie um arquivo `.env`

Na raiz do projeto, crie um arquivo chamado:

```bash
.env
```

E adicione sua chave da API:

```bash
GROQ_API_KEY=sua_chave_aqui
```

---

### 4. Rodar o projeto

Você pode abrir o arquivo `index.html` diretamente no navegador.

Ou usar uma extensão como Live Server no VS Code.

---

## ⚠️ Observações

- Para que a geração de páginas funcione corretamente, é necessário configurar a variável de ambiente com sua própria chave de API.
- O projeto foi desenvolvido com foco em aprendizado e portfólio.

---

## 📌 Autor

Desenvolvido por Michael Moura 🚀
