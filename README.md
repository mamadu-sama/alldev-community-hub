<p align="center">
  <img src="https://img.shields.io/badge/Alldev-Developer%20Community-6366f1?style=for-the-badge&logo=dev.to&logoColor=white" alt="Alldev" />
</p>

<h1 align="center">🚀 Alldev Community Hub</h1>

<p align="center">
  <strong>Uma comunidade global para programadores partilharem conhecimento, resolverem problemas e crescerem juntos.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Development-yellow?style=flat-square" alt="Status" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License" />
  <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=flat-square" alt="Contributions" />
</p>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-repositórios">Repositórios</a> •
  <a href="#-funcionalidades">Funcionalidades</a> •
  <a href="#-arquitetura">Arquitetura</a> •
  <a href="#-começar">Começar</a> •
  <a href="#-contribuir">Contribuir</a> •
  <a href="#-roadmap">Roadmap</a>
</p>

---

## 📖 Sobre o Projeto

O **Alldev** é uma plataforma comunitária moderna de ecossistema completo onde programadores de todo o mundo podem:

- 💬 **Partilhar conhecimento** através de posts técnicos e discussões detalhadas
- ❓ **Resolver problemas** colaborativamente com a ajuda da comunidade
- ⭐ **Ganhar reputação** através de contribuições de qualidade e consistência
- 🏷️ **Descobrir conteúdo** por tags, pesquisa avançada e recomendações personalizadas
- 👤 **Construir perfis profissionais** que destacam competências, contribuições e histórico
- 🎯 **Crescer profissionalmente** através de gamificação e sistema de níveis

Este repositório serve como **hub organizacional** que conecta todos os componentes do projeto Alldev.

---

## 📦 Repositórios

O projeto Alldev está dividido em repositórios independentes para facilitar o desenvolvimento, deploy e manutenção:

### 🎨 Frontend

**Repositório**: [alldev-frontend](https://github.com/mamadu-sama/alldev-frontend)

Interface do usuário moderna e responsiva construída com as melhores práticas de desenvolvimento web.

**Tecnologias principais:**

- ⚛️ React 18.3 + TypeScript 5.0
- ⚡ Vite 5.0 (Build ultra-rápido)
- 🎨 Tailwind CSS 3.4 + Shadcn/UI
- 🔄 TanStack Query (React Query v5)
- 🐻 Zustand (Estado global)
- 🛣️ React Router v6

```bash
# Clonar apenas o frontend
git clone https://github.com/mamadu-sama/alldev-frontend.git
cd alldev-frontend
npm install
npm run dev
```

📖 **[Ver documentação completa do Frontend →](https://github.com/mamadu-sama/alldev-frontend/blob/main/docs/FRONTEND_DOCUMENTATION.md)**

---

### ⚙️ Backend

**Repositório**: [alldev-backend](https://github.com/mamadu-sama/alldev-backend)

API REST robusta e escalável com autenticação, autorização e todas as funcionalidades da plataforma.

**Tecnologias principais:**

- 🟢 Node.js 18+ + Express.js
- 📘 TypeScript
- 🐘 PostgreSQL 15+
- 🔷 Prisma ORM
- 🔐 JWT Authentication
- 🐳 Docker + Docker Compose
- 🚀 Redis (Cache - opcional)

**Deploy sugerido:** Railway, Render, DigitalOcean, AWS

```bash
# Clonar apenas o backend
git clone https://github.com/mamadu-sama/alldev-backend.git
cd alldev-backend
npm install
docker-compose up -d  # Subir PostgreSQL
npm run dev
```

📖 **[Ver documentação completa do Backend →](https://github.com/mamadu-sama/alldev-backend/blob/main/docs/BACKEND_DOCUMENTATION.md)**

---

## ✨ Funcionalidades

### 👥 Para Utilizadores

| Funcionalidade                 | Descrição                                                        | Status |
| ------------------------------ | ---------------------------------------------------------------- | ------ |
| 🔐 **Autenticação Completa**   | Registo, login, recuperação de password, verificação de email    | ✅     |
| 📝 **Sistema de Posts**        | Criar, editar, eliminar posts com Markdown e syntax highlighting | ✅     |
| 💬 **Comentários Interativos** | Sistema hierárquico com respostas aceites e threads              | ✅     |
| 👍 **Sistema de Votação**      | Upvote/downvote em posts e comentários com proteção anti-spam    | ✅     |
| 🔔 **Notificações Real-time**  | Alertas para menções, respostas, votos e marcos alcançados       | ✅     |
| 🔍 **Pesquisa Avançada**       | Pesquisa full-text por posts, utilizadores, tags com filtros     | ✅     |
| 🏷️ **Sistema de Tags**         | Organização de conteúdo por categorias e subcategorias           | ✅     |
| 👤 **Perfis Personalizáveis**  | Bio, competências, links sociais, portfolio e estatísticas       | ✅     |
| 🏆 **Sistema de Reputação**    | 4 níveis: Novato → Contribuidor → Expert → Guru                  | ✅     |
| 📊 **Dashboard Pessoal**       | Visão geral de atividade, conquistas e estatísticas              | 🚧     |
| 🌙 **Modo Escuro/Claro**       | Alternância de tema com preferência salva                        | ✅     |
| 🌍 **Internacionalização**     | Suporte multi-idioma (PT, EN, ES)                                | 🔮     |

### 🛡️ Para Administradores

| Funcionalidade                 | Descrição                                        | Status |
| ------------------------------ | ------------------------------------------------ | ------ |
| 📊 **Dashboard Admin**         | Métricas em tempo real e estatísticas detalhadas | ✅     |
| 👥 **Gestão de Utilizadores**  | CRUD completo, atribuição de roles, banimentos   | ✅     |
| 📋 **Gestão de Conteúdo**      | Moderar posts, comentários e processar denúncias | ✅     |
| ⚙️ **Configurações Globais**   | Modo manutenção, limites de API, features flags  | ✅     |
| 📢 **Sistema de Notificações** | Envio de notificações em massa para utilizadores | ✅     |
| 📈 **Analytics**               | Relatórios de uso, engagement e crescimento      | 🚧     |
| 🔒 **Logs de Auditoria**       | Rastreamento de ações administrativas            | 🚧     |

### ⚖️ Para Moderadores

| Funcionalidade             | Descrição                                        | Status |
| -------------------------- | ------------------------------------------------ | ------ |
| 📥 **Fila de Moderação**   | Gerir conteúdo reportado por ordem de prioridade | ✅     |
| ✏️ **Edição de Posts**     | Editar, ocultar ou destacar posts problemáticos  | ✅     |
| 🔒 **Controle de Threads** | Bloquear/desbloquear comentários em discussões   | ✅     |
| ⚠️ **Sistema de Avisos**   | Enviar avisos formais a utilizadores             | ✅     |
| 📊 **Relatórios**          | Estatísticas de moderação e eficiência           | 🚧     |

**Legenda:** ✅ Implementado | 🚧 Em Desenvolvimento | 🔮 Planeado

---

## 🏗️ Arquitetura

```
┌─────────────────────────────────────────────────────────────┐
│                        ALLDEV PLATFORM                        │
└─────────────────────────────────────────────────────────────┘

┌──────────────────┐          ┌──────────────────┐
│                  │          │                  │
│    FRONTEND      │◄────────►│     BACKEND      │
│                  │   REST    │                  │
│   React + TS     │   API     │   Node.js + TS   │
│   Tailwind UI    │          │   Express + JWT   │
│   TanStack Query │          │   Prisma ORM     │
│                  │          │                  │
└──────────────────┘          └─────────┬────────┘
                                        │
                              ┌─────────▼────────┐
                              │                  │
                              │   PostgreSQL     │
                              │   Database       │
                              │                  │
                              └──────────────────┘
```

### 🔄 Fluxo de Dados

1. **Cliente** faz request → **Frontend** (React)
2. **Frontend** comunica via REST API → **Backend** (Express)
3. **Backend** autentica com JWT → valida dados
4. **Backend** consulta/atualiza → **PostgreSQL** (via Prisma)
5. **Backend** retorna resposta → **Frontend** atualiza UI

---

## 🚀 Começar

### 📋 Pré-requisitos

- Node.js 18+ ([Download](https://nodejs.org/))
- npm, yarn ou bun
- Git
- Docker (opcional, para PostgreSQL local)
- PostgreSQL 15+ (se não usar Docker)

### ⚡ Setup Rápido

#### Opção 1: Setup Manual

```bash
# 1. Clonar frontend
git clone https://github.com/mamadu-sama/alldev-frontend.git
cd alldev-frontend
npm install
npm run dev
# Frontend rodando em http://localhost:5173

# 2. Clonar backend (em outra janela do terminal)
git clone https://github.com/mamadu-sama/alldev-backend.git
cd alldev-backend
npm install

# 3. Configurar banco de dados
docker-compose up -d  # ou configure PostgreSQL manualmente

# 4. Configurar variáveis de ambiente
cp .env.example .env
# Editar .env com suas configurações

# 5. Rodar migrações
npx prisma migrate dev

# 6. Iniciar backend
npm run dev
# Backend rodando em http://localhost:3000
```

#### Opção 2: Script Automatizado

```bash
# 1. Clonar este repositório organizador
git clone https://github.com/seu-usuario/alldev-community-hub.git
cd alldev-community-hub

# 2. Rodar script de setup
chmod +x setup.sh
./setup.sh

# O script irá:
# - Clonar frontend e backend
# - Instalar todas as dependências
# - Configurar arquivos .env
# - Subir containers Docker
# - Rodar migrações do banco
```

### 📁 Estrutura Recomendada Localmente

```
seu-workspace/
├── alldev-frontend/          # Repositório frontend
│   ├── src/
│   ├── public/
│   ├── docs/
│   └── package.json
│
├── alldev-backend/           # Repositório backend
│   ├── src/
│   ├── prisma/
│   ├── docs/
│   └── package.json
│
└── alldev-community-hub/     # Este repositório (organizador)
    ├── README.md
    ├── setup.sh
    └── docs/
```

---

## 🤝 Contribuir

Contribuições são extremamente bem-vindas! O Alldev é um projeto comunitário e cresce com a ajuda de pessoas como você.

### 🎯 Como Contribuir

1. **Escolha um repositório**: Frontend ou Backend
2. **Fork o projeto** no GitHub
3. **Clone seu fork**: `git clone https://github.com/mamdu-sama/alldev-[frontend|backend].git`
4. **Crie uma branch**: `git checkout -b feature/MinhaNovaFuncionalidade`
5. **Faça suas alterações** seguindo as convenções de código
6. **Teste suas mudanças** localmente
7. **Commit**: `git commit -m "feat: adiciona nova funcionalidade X"`
8. **Push**: `git push origin feature/MinhaNovaFuncionalidade`
9. **Abra um Pull Request** no repositório original

### 📝 Convenções de Commit

Seguimos [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: nova funcionalidade
fix: correção de bug
docs: mudanças na documentação
style: formatação, ponto e vírgula, etc
refactor: refatoração de código
test: adicionar/modificar testes
chore: atualização de build, deps, etc
```

### 🐛 Reportar Bugs

Encontrou um bug? Abra uma issue no repositório correspondente:

- 🎨 **Bug no Frontend**: [Issues Frontend](https://github.com/seu-usuario/alldev-frontend/issues)
- ⚙️ **Bug no Backend**: [Issues Backend](https://github.com/seu-usuario/alldev-backend/issues)

### 💡 Sugerir Funcionalidades

Tem uma ideia? Adoraríamos ouvir! Abra uma issue com a tag `enhancement`.

### 📚 Áreas que Precisam de Ajuda

- 🌍 Traduções (internacionalização)
- 📝 Melhorias na documentação
- 🎨 Design de UI/UX
- 🧪 Testes automatizados
- ♿ Melhorias de acessibilidade
- 🚀 Otimizações de performance

---

## 🗺️ Roadmap

### 🎯 Versão 1.0 (Q1 2024)

- [x] Autenticação completa
- [x] CRUD de posts e comentários
- [x] Sistema de votação
- [x] Perfis de usuário
- [x] Sistema de tags
- [ ] Notificações em tempo real (WebSocket)
- [ ] Testes E2E completos

### 🚀 Versão 2.0 (Q2 2024)

- [ ] Sistema de mensagens privadas
- [ ] Gamificação avançada (badges, conquistas)
- [ ] Feed personalizado com algoritmo de recomendação
- [ ] Editor de código com preview
- [ ] Integração com GitHub/GitLab
- [ ] API pública para desenvolvedores

### 🌟 Futuro

- [ ] Aplicativo mobile (React Native)
- [ ] Live coding/streaming
- [ ] Marketplace de serviços
- [ ] Sistema de mentorias
- [ ] Certificações da comunidade

---

## 📚 Documentação Completa

| Documento            | Descrição                               | Link                                                                                             |
| -------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------ |
| 📱 **Frontend Docs** | Arquitetura, componentes, rotas, estado | [Ver →](https://github.com/mamadu-sama/alldev-frontend/blob/main/docs/FRONTEND_DOCUMENTATION.md) |
| ⚙️ **Backend Docs**  | API, autenticação, banco de dados       | [Ver →](https://github.com/mamadu-sama/alldev-backend/blob/main/docs/BACKEND_DOCUMENTATION.md)   |

---

## 🛠️ Stack Tecnológica Completa

### Frontend

```yaml
Core:
  - React 18.3
  - TypeScript 5.0
  - Vite 5.0

Estilização:
  - Tailwind CSS 3.4
  - Shadcn/UI
  - Lucide Icons
  - Radix UI

Estado:
  - TanStack Query (React Query v5)
  - Zustand
  - React Hook Form

Roteamento:
  - React Router v6

Validação:
  - Zod

Markdown:
  - React Markdown
  - Syntax Highlighter
```

### Backend

```yaml
Runtime:
  - Node.js 18+
  - TypeScript 5.0

Framework:
  - Express.js

Banco de Dados:
  - PostgreSQL 15+
  - Prisma ORM

Autenticação:
  - JWT
  - bcrypt

Cache (opcional):
  - Redis
  - ioredis

DevOps:
  - Docker
  - Docker Compose

Testes:
  - Jest
  - Supertest
```

---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT** - consulte os arquivos LICENSE em cada repositório para detalhes.

```
MIT License - você pode usar, copiar, modificar e distribuir livremente.
```

---

## 👥 Equipe e Contribuidores

Este projeto é mantido pela comunidade Alldev. Agradecemos a todos os contribuidores que ajudam a tornar esta plataforma melhor!

[![Contributors](https://img.shields.io/github/contributors/mamadu-sama/alldev-frontend?style=flat-square)](https://github.com/mamadu-sama/alldev-frontend/graphs/contributors)

---

## 💬 Comunidade e Suporte

- 💬 **Discord**: [Entrar no servidor](https://discord.gg/alldev) (em breve)
- 🐦 **Twitter**: [@alldev_community](https://twitter.com/alldev_community)
- 📧 **Email**: contact@alldev.pt
- 🌐 **Website**: [alldev.community](https://alldev.dev)

---

## 🌟 Mostrar Suporte

Se você gosta deste projeto, considere:

- ⭐ Dar uma estrela nos repositórios
- 🐛 Reportar bugs e sugerir melhorias
- 💻 Contribuir com código
- 📢 Compartilhar com outros desenvolvedores
- ☕ [Buy me a coffee](https://buymeacoffee.com/alldev) (opcional e em breve)

---

## 📊 Status do Projeto

| Métrica      | Status                                                                                    |
| ------------ | ----------------------------------------------------------------------------------------- |
| Build        | ![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square) |
| Coverage     | ![Coverage](https://img.shields.io/badge/coverage-78%25-yellow?style=flat-square)         |
| Version      | ![Version](https://img.shields.io/badge/version-0.9.0-blue?style=flat-square)             |
| Contributors | ![Contributors](https://img.shields.io/badge/contributors-12-orange?style=flat-square)    |

---

<p align="center">
  <strong>Junta-te à nossa comunidade global de programadores!</strong>
</p>

<p align="center">
  O Alldev é um espaço inclusivo onde programadores de todas as origens, níveis de experiência e backgrounds são bem-vindos. Acreditamos que a partilha de conhecimento e a colaboração tornam toda a comunidade tech mais forte e inovadora.
</p>

<p align="center">
  <strong>🚀 Vamos construir o futuro do desenvolvimento de software juntos! 🚀</strong>
</p>

---

<p align="center">
  Feito com ❤️ pela comunidade Alldev<br>
  <sub>Última atualização: Dezembro 2025</sub>
</p>
