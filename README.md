# 🧭 TeamBoard SaaS

**TeamBoard** é uma aplicação **SaaS de gerenciamento de projetos e tarefas para equipes**, inspirada em ferramentas como Trello e Jira.  
O sistema foi desenvolvido como projeto demonstrativo full-stack, com **autenticação JWT**, **painel Kanban**, **relatórios de produtividade** e **pipeline CI/CD automatizado**.

---

## 🚀 Tecnologias Utilizadas

### 🧩 Backend
- **Node.js** + **TypeScript**
- **Express** (API REST)
- **PostgreSQL** (banco de dados relacional)
- **Prisma ORM** ou **TypeORM** (persistência de dados)
- **JWT / bcryptjs** (autenticação segura)
- **Jest + Supertest** (testes)

### 💻 Frontend
- **React** + **TypeScript**
- **Vite** (build rápido)
- **TailwindCSS** (estilização)
- **Axios** (requisições HTTP)
- **Zustand** (gerenciamento de estado)
- **React Router DOM**

### ⚙️ DevOps / Infra
- **Docker & Docker Compose**
- **GitHub Actions** (CI/CD)
- **Terraform** *(opcional, para IaC e deploy AWS)*
- **Swagger / OpenAPI** (documentação da API)

---

## 🧱 Arquitetura

O projeto segue uma arquitetura **monorepo**, dividida entre serviços de frontend e backend, com suporte a **containerização via Docker**.

