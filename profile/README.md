# 🚀 GitHub Repo Templates Hub

Bem-vindo ao **Templates Hub**, o repositório central para criação de novos projetos via **GitHub Templates**! Aqui você encontra modelos prontos para uso, com boas práticas, estrutura organizada e ferramentas configuradas.

---

## 📦 O que é isso?

Este repositório serve como um **catálogo de templates** para acelerar a criação de novos projetos no GitHub, organizando por tipos de aplicação, tecnologia e finalidade.

---

## 🧭 Como usar?

Basta clicar em um dos botões abaixo para **criar um novo repositório** com base em um template:

---

## 🗂️ Templates disponíveis

| Template         | Descrição                                     | Criar Repositório                                  |
|------------------|-----------------------------------------------|----------------------------------------------------|
| `template-lambda`  | Microservice em lambda com GO Lang     | [![Usar Template](https://img.shields.io/badge/%F0%9F%9A%80%20Usar%20Template-blue?style=for-the-badge)](https://github.com/postalllog/lambda-template/generate)   |
| `template-front-end-react-vite`  | Front-End com design system da postall     | [![Usar Template](https://img.shields.io/badge/%F0%9F%9A%80%20Usar%20Template-blue?style=for-the-badge)](https://github.com/postalllog/fe-template/generate)   |
| `template-lambda-csharp`  | Microservice em lambda com Csharp     | [![Usar Template](https://img.shields.io/badge/%F0%9F%9A%80%20Usar%20Template-blue?style=for-the-badge)](https://github.com/postalllog/lambda-template-csharp/generate)   |


> ✅ *Todos os templates seguem boas práticas de estrutura, versionamento, testes e documentação.*

---

## 🧑‍💻 Para colaboradores

### Adicionar um novo template:

1. Crie uma nova pasta ou repositório separado com o nome `nome-template`.
2. Marque o repositório como **template** nas configurações do GitHub.
3. Adicione um `README.md` explicativo dentro do template.
4. Atualize a tabela acima com o link `https://github.com/postalllog/template-nome/generate`.

---

## 💡 Dica rápida

Use o [GitHub CLI](https://cli.github.com/) para criar repositórios a partir dos templates:

```bash
gh repo create meu-projeto --template postalllog/template-node --private
