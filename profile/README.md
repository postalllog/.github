<div align="center">

# 🚀 **Postall Log**
### *Desafiando o tempo o tempo todo!*

</div>

## 📦 **Catálogo de Soluções**

> 🎯 **Repositórios oficiais da Postall Log** para acelerar o desenvolvimento de aplicações, microsserviços e infraestrutura.

Este catálogo reúne:
- 🧩 **Templates de projeto** prontos para uso
- 🏗️ **Repositórios base de infraestrutura**
- 📐 **Padrões arquiteturais adotados pela empresa**

---

## 🧩 **Templates de Desenvolvimento**

> Utilize estes templates para **criar novos projetos** seguindo os padrões oficiais da Postall Log.

| 🏷️ Nome | 📝 Descrição | 🚀 Criar Projeto |
|:---|:---|:---:|
| **Lambda Go** | Microserviço serverless em Go Lang, com CI/CD, testes e boas práticas | [![Usar Template](https://img.shields.io/badge/🚀%20Usar%20Template-4CAF50?style=for-the-badge)](https://github.com/postalllog/lambda-template/generate) |
| **React + Vite** | Frontend moderno com Design System, Vite e arquitetura escalável | [![Usar Template](https://img.shields.io/badge/🚀%20Usar%20Template-61DAFB?style=for-the-badge)](https://github.com/postalllog/fe-template/generate) |
| **Lambda C#** | Microserviço serverless em C# (.NET) com estrutura pronta para produção | [![Usar Template](https://img.shields.io/badge/🚀%20Usar%20Template-9C27B0?style=for-the-badge)](https://github.com/postalllog/lambda-template-csharp/generate) |

---

## 🏗️ **Infraestrutura e Repositórios Base**

> Repositórios utilizados como **fundação da plataforma**, não destinados à geração de novos projetos.

| 🏷️ Nome | 📝 Descrição | 🔗 Acesso |
|:---|:---|:---:|
| **API Gateway (Não PROD)** | Gateway de APIs para roteamento, autenticação, versionamento e políticas de acesso | [![Ver Repositório](https://img.shields.io/badge/📦%20Ver%20Repositório-607D8B?style=for-the-badge)](https://github.com/postalllog/infra-apigtw-nonprod) |

---

## 🎯 **Como Começar**

### 🔧 Criando um novo projeto a partir de um template

#### Usando GitHub CLI
```bash
gh repo create meu-projeto \
  --template postalllog/lambda-template \
  --private
