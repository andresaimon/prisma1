
<h1 align="center">
Node.js + Express + Typescript + Prisma + MySQL
</h1>

<p> Rocketseat Tutorial </p>
<p> Video: https://www.youtube.com/watch?v=nuLTwqPNq-w</p>
<p> Original Code: https://github.com/rocketseat-content/prisma_decode </p>

## Node.js
- "Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine."
- https://nodejs.org/en/

- I installed Node.js using Ubuntu 20.04.3 LTS operating system following the link below:
- https://github.com/nodesource/distributions/blob/master/README.md

- And I use the npm like package manager. You can install following the insctructions in the link below:
- https://www.npmjs.com/package/npm

- For init a new aplication using the npm package manager, you just need to use the next comand:
- ```npm run dev```

## Express
- "Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications."
- https://expressjs.com/

- When you open this project, you need to install the Express, then creating it the node_modules folder.
- The comand to iniciate this is: ```npm install express```

## Typescript
- "TypeScript is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale."
- https://www.typescriptlang.org/

## Prisma
- "Prisma helps app developers build faster and make fewer errors with an open source database toolkit for PostgreSQL, MySQL, SQL Server, SQLite and MongoDB (Preview)."
- https://www.prisma.io/

- For init a Prisma project using Node.js and Typescript, you need to run the next comands:
- ```npm install prisma typescript ts-node @types/node –save-dev```
- ```npm i --save-dev @types/express```
- ```npm i ts-node-dev --save-dev```

- Now, you can see the new file ```tsconfig.json``` and you need to configurate like the documentation steps
- https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases-typescript-postgres

- In VSCode, you can use the Prisma extension
- "Adds syntax highlighting, formatting, auto-completion, jump-to-definition and linting for .prisma files."
- https://marketplace.visualstudio.com/items?itemName=Prisma.prisma

- For init the Prisma aplication, you need to use the comand: ```npx prisma init```

## MySQL
- If you need install the MySQL in your Ubuntu machine, you can see this tutorial: https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-20-04-pt
- You can follow the next links to make a configuration between the Node.js and the MySQL: 
- https://www.youtube.com/watch?v=NkJwjy3LOd4
- https://www.webmundi.com/banco-de-dados/mysql/como-instalar-mysql-mysql-workbench-no-linux/
- For init the database, you can use the next comand: 
```mysql -h localhost -u root -p```

- You need to configurate the MySQL in the files ```shema.prisma``` and ```.env``` like the steps in documentation:
- https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases/connect-your-database-typescript-mysql

- Now, you can use the comands in Prisma for manipulate your data base, from the Prisma Migrate:
- https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases/using-prisma-migrate-typescript-postgres
- ```npx prisma migrate dev```

- You can create news models and relations, and validate the implementation of the params with the comand:
- ```npx prisma format```
