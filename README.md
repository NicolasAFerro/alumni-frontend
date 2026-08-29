# Sistema Alumni FATEC Sorocaba

Sistema de gerenciamento de ex-alunos da FATEC Sorocaba desenvolvido como Trabalho de Conclusão de Curso (TCC).

## Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Configuração e Instalação](#configuração-e-instalação)
- [Comandos de Desenvolvimento](#comandos-de-desenvolvimento)
- [Funcionalidades](#funcionalidades)
- [Autores](#autores)

## Sobre o Projeto

O Sistema Alumni FATEC Sorocaba é um projeto desenvolvido como Trabalho de Conclusão de Curso pelos alunos [Leonardo Silva](https://www.linkedin.com/in/leonardo-barbosa-da-silva-085858230/), [Gabriel Bellato](https://www.linkedin.com/in/gabriel-silva-bellato/) e [Nicolas Ferro](https://www.linkedin.com/in/nicolas-alexandrino-ferro/), sob orientação da Professora Denilce.

O objetivo é criar uma plataforma para conectar alunos e ex-alunos da FATEC Sorocaba, facilitando o networking, oportunidades de carreira e manutenção do vínculo com a instituição.

## Tecnologias Utilizadas

- **[Next.js 15.5.4](https://nextjs.org)** - Framework React com Turbopack para builds otimizados
- **[React 19.1.0](https://reactjs.org)** - Biblioteca para construção de interfaces
- **[TypeScript](https://www.typescriptlang.org)** - Tipagem estática para JavaScript
- **[Tailwind CSS v4](https://tailwindcss.com)** - Framework CSS utilitário

## Estrutura do Projeto

```
alumni-frontend/
├── src/
│   ├── app/
│   │   ├── globals.css      # Estilos globais e variáveis de cor
│   │   ├── layout.tsx       # Layout principal da aplicação
│   │   └── page.tsx         # Página inicial
│   └── ...
├── public/                  # Arquivos estáticos
├── next.config.ts          # Configuração do Next.js
├── package.json            # Dependências e scripts
└── README.md               # Este arquivo
```

## Configuração e Instalação

### Pré-requisitos

- **Node.js** (versão 18 ou superior)
- **npm** (vem com o Node.js)

### Passos para Instalação

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/NicolasAFerro/alumni-frontend.git
   cd alumni-frontend
   ```

2. **Instale as dependências:**

   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento:**

   ```bash
   npm run dev
   ```

4. **Acesse a aplicação:**
   Abra [http://localhost:3000](http://localhost:3000) no seu navegador.

## Comandos de Desenvolvimento

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev

# Criar build de produção
npm run build

# Iniciar servidor de produção (após build)
npm start

# Executar linting
npx next lint
```

## Funcionalidades

### Implementadas

- ✅ Configuração do tema com cores oficiais da FATEC Sorocaba
- ✅ Tipografia personalizada (Roboto Slab + Roboto)
- ✅ Estrutura base do projeto Next.js
- ✅ Configuração do Tailwind CSS personalizado
- ✅ Página de demonstração do sistema de cores

### Em Desenvolvimento

- 🔄 Sistema de autenticação de usuários
- 🔄 Cadastro e perfil de ex-alunos
- 🔄 Gerenciamento de eventos
- 🔄 Portal de vagas de emprego
- 🔄 Sistema de usuários
- 🔄 Painel administrativo
- 🔄 Sistema de chat (menor prioridade)

### Planejadas

## Autores

Desenvolvido como Trabalho de Conclusão de Curso na FATEC Sorocaba.

**Desenvolvedores:**

- [Leonardo Silva](https://www.linkedin.com/in/leonardo-barbosa-da-silva-085858230/)
- [Gabriel Bellato](https://www.linkedin.com/in/gabriel-silva-bellato/)
- [Nicolas Ferro](https://www.linkedin.com/in/nicolas-alexandrino-ferro/)

**Orientador:**

- Professor Jarbas

**Instituição:**

- [FATEC Sorocaba](https://fatecsorocaba.cps.sp.gov.br/)

---

# Alumni FATEC Sorocaba System

Alumni management system for FATEC Sorocaba developed as a Final Course Project (TCC).

## Table of Contents

- [About the Project](#about-the-project)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Development Commands](#development-commands)
- [Features](#features)
- [Authors](#authors)

## About the Project

The Alumni FATEC Sorocaba System is a project developed as a Final Course Project by students [Leonardo Silva](https://linkedin.com/in/leonardo-silva), [Gabriel Bellato](https://linkedin.com/in/gabriel-bellato), and [Nicolas Ferro](https://linkedin.com/in/nicolas-ferro), under the guidance of Professor Jarbas.

The goal is to create a platform to connect and manage FATEC Sorocaba alumni, facilitating networking, career opportunities, and maintaining ties with the institution.

## Technologies Used

- **[Next.js 15.5.4](https://nextjs.org)** - React framework with Turbopack for optimized builds
- **[React 19.1.0](https://reactjs.org)** - Library for building user interfaces
- **[TypeScript](https://www.typescriptlang.org)** - Static typing for JavaScript
- **[Tailwind CSS v4](https://tailwindcss.com)** - Utility-first CSS framework

## Project Structure

```
alumni-frontend/
├── src/
│   ├── app/
│   │   ├── globals.css      # Global styles and color variables
│   │   ├── layout.tsx       # Main application layout
│   │   └── page.tsx         # Home page
│   └── ...
├── public/                  # Static files
├── next.config.ts          # Next.js configuration
├── package.json            # Dependencies and scripts
└── README.md               # This file
```

## Setup and Installation

### Prerequisites

- **Node.js** (version 18 or higher)
- **npm** (comes with Node.js)

### Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/NicolasAFerro/alumni-frontend.git
   cd alumni-frontend
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm run dev
   ```

4. **Access the application:**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Development Commands

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Create production build
npm run build

# Start production server (after build)
npm start

# Run linting
npx next lint
```

## Features

### Implemented

- ✅ Theme configuration with official FATEC Sorocaba colors
- ✅ Custom typography (Roboto Slab + Roboto)
- ✅ Next.js project base structure
- ✅ Custom Tailwind CSS configuration
- ✅ Color system demonstration page

### In Development

- 🔄 User authentication system
- 🔄 Alumni registration and profiles
- 🔄 Event management system
- 🔄 Job portal
- 🔄 User management system
- 🔄 Administrative dashboard
- 🔄 Chat system (lower priority)

### Planned

- 📋 Administrative dashboard
- 📋 Messaging system
- 📋 Social media integration
- 📋 Reports and statistics
- 📋 Notification system
- 📋 Mobile application

## Authors

Developed as a Final Course Project at FATEC Sorocaba.

**Developers:**

- [Leonardo Silva](https://www.linkedin.com/in/leonardo-barbosa-da-silva-085858230/)
- [Gabriel Bellato](https://www.linkedin.com/in/gabriel-silva-bellato/)
- [Nicolas Ferro](https://www.linkedin.com/in/nicolas-alexandrino-ferro/)

**Advisor:**

- Professor Jarbas

**Institution:**

- [FATEC Sorocaba](https://fatecsorocaba.cps.sp.gov.br/)
