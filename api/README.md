# <h1 id="top" align="center">NLW Pocket 📋📆 Projeto Backend API </h1>

<p align="center">
  <a href="#sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#-features">Features</a> &#xa0; | &#xa0;
  <a href="#-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#-requisitos">Requisitos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-iniciando">Iniciando</a> &#xa0; | &#xa0;
  <a href="https://github.com/RodrigoLuigi" target="_blank">Author</a>
</p>

## <img id="sobre" src="https://imgur.com/VhTBbHg.png" alt="imagem de um notebook" align="center" width="30px"> _**O que desenvolvemos neste Projeto?**_

**in.Orbit**

Uma aplicação para gerenciamento de metas gamificada, onde o usuário cadastra metas semanais e pode controlar em tempo real a pontuação.

Desenvolvimento de uma aplicação back-end em Node.js, aplicação dos conceitos de API REST, utilizando TypeScript, Fastify como framework, integração do DrizzleORM + PostgreSQL, Docker e Zod para validação de dados.

## ⚙️ Features ##

:heavy_check_mark: Criação de metas\
:heavy_check_mark: Criação de metas completas\
:heavy_check_mark: Listar metas pendentes\
:heavy_check_mark: Listar metas concluídas da semana

## 👨‍💻 Tecnologias ##

As seguintes ferramentas foram usadas neste projeto:

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)

## 📚️ Bibliotecas ##

As seguintes bibliotecas e ferramentas foram usadas neste projeto:

- [TypeScript](https://www.typescriptlang.org/)
  - Instalação: `npm i typescript -D`
  - Inicializar TypeScript: `npx tsx -init`
  - Configuração do tsconfig bases: [tsconfig bases (GitHub repo)](https://github.com/tsconfig/bases)

- [@types/node](https://www.npmjs.com/package/@types/node) e [TSX](https://www.npmjs.com/package/tsx)
  - Instalação: `npm i @types/node tsx -D`

- [Fastify](https://www.fastify.io/)
  - Instalação: `npm i fastify`

- [Biome](https://biomejs.dev/)
  - Instalação: `npm i -D --save-exact @biomejs/biome`

- [Drizzle ORM](https://orm.drizzle.team/)
  - Instalação: `npm i drizzle-orm`
  - Instalação do CLI: `npm i drizzle-kit -D`
  - Gerar migrações: `npx drizzle-kit generate`
  - Aplicar migrações: `npx drizzle-kit migrate`

- [Zod](https://www.npmjs.com/package/zod)
  - Instalação: `npm i zod`

- [Postgres](https://www.npmjs.com/package/postgres)
  - Instalação: `npm i postgres`

- [Cuid2](https://www.npmjs.com/package/@paralleldrive/cuid2)
  - Instalação: `npm i @paralleldrive/cuid2`

- [Day.js](https://day.js.org/)
  - Instalação: `npm i dayjs`

- [Fastify Type Provider Zod](https://www.npmjs.com/package/fastify-type-provider-zod)
  - Instalação: `npm i fastify-type-provider-zod`

## 📝 Requisitos ##

- [Git](https://git-scm.com) 
- [Node](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)

## :checkered_flag: Iniciando ##

```bash
# Clone este projeto (server)
$ git clone https://github.com/RodrigoLuigi/nlw-pocket.git
# Acesse o projeto
$ cd api
# Instale as dependências
$ npm install
# Criar arquivo .env e configurar variáveis de ambiente
DATABASE_URL:
# Rode as migrations
$ npx drizzle-kit migrate
# Seeds
$ npm run seeds
# Execute o projeto com npm
$ npm run dev
# O Server irá inicializar em http://localhost:3333
```

## 🔗 Rotas ##

```bash
# [POST] Cadastrar meta
/goals
# [POST] Registra meta completa
/completions
# [GET] Listar metas pendentes
/pending-goals
# [GET] Listar resumo de metas da semana
/summary

```

##
_**Feito por <a href="https://github.com/RodrigoLuigi" target="_blank">Rodrigo Luigi</a>**_  👨‍🚀 :rocket:

&#xa0;

<a href="#top">Back to top</a>