# Prisma Project

> Amalgam of SLSTAR, PRASTAR & DOCSTAR

### Getting Started

1.  After cloning, run:

```bash
npx repo-genesis-cli .repogen.js
```

2.  After repo-genesis finishes, copy/paste/run the following in your terminal (from prisma-project directory):

```bash
cd aws-sls-auth-starter && npm install \
&& cd ../prisma-authorized-starter && npm install \
&& cd ../
```

### Projects

**Moniker**

> Shorthand for identifying the projects throughout the documentation

| Project Directory           | Project Alias |
| :-------------------------- | :------------ |
| `aws-sls-auth-starter`      | SLSTAR        |
| `prisma-authorized-starter` | PRASTAR       |
| `docsify-starter`           | DOCSTAR       |

**Description**

> What role these projects play within prisma-project

| What                        | Why                                                |
| :-------------------------- | :------------------------------------------------- |
| `aws-sls-auth-starter`      | Serverless API, JWT Authorization                  |
| `prisma-authorized-starter` | SLSTAR-compatible authorization prisma boilerplate |
| `docsify-starter`           | Docs for all of `prisma-project`                   |

**Source Control**

| Project | Github                              | NPM |
| :------ | :---------------------------------- | :-- |
| SLSTAR  | @servexyz/aws-sls-auth-starter      | N/A |
| PRASTAR | @servexyz/prisma-authorized-starter | N/A |
| DOCSTAR | @servexyz/docsify-starter           | N/A |

**Running**

| Project | Run Command                             | Port             |
| :------ | :-------------------------------------- | :--------------- |
| SLSTAR  | **npm start**                           | 3000             |
| PRASTAR | **docker-compose up -d && npm run dev** | 4000, 4466, 3306 |
| DOCSTAR | **docker-compose up -d**                | 3099             |
