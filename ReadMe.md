# Simple JWT authentication server app

This project was created with [Typescript](https://www.typescriptlang.org/) and [PrismaOrm](https://www.prisma.io/) and  [Fastify](https://www.fastify.io/).

## Available Scripts

You need to start projects seperately.

*In project directory, you can run:

### `cd fastify-ts-prismaOrm-auth-example`


### `npm install`
Do not forget to install dependencies

### `npx prisma db seed`
It will seed your database. Please do not forget to connect yourn own database.

### `npm run start`

Runs the app in the development mode.\
Open [http://localhost:5000](http://localhost:5000) to view it in the browser.


### `.env database connection`

mysql://USER:PASSWORD@HOST:PORT/DATABASE


### `npx prisma migrate dev`

Create the first migration.\
See the section about [prisma migrate](https://www.prisma.io/docs/concepts/components/prisma-migrate) for more information.

### `npx prisma generate`

To generate and instantiate Prisma Client:

Ensure that you have Prisma CLI installed on your machine.

Add the following generator definition to your Prisma schema:

See the section about [Prisma Generate](https://www.prisma.io/docs/concepts/components/prisma-client/working-with-prismaclient/generating-prisma-client) for more information.


*In project directory, you can run:

### `cd ts-react-auth-example`


### `npm install`
Do not forget to install dependencies


### `npm run start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.



- In this project you can CRUD operations fulfill.

- You can register, activate, login, unlogin, update and delete user and call users and their forecasts.

- Message to the user did not coded yet. Therefore activation can be done after registration by sending a request to the http://localhost:3000/activate/<active_token>. you can send by yourself.

-After login you will see the private page of customers. If you are manager you can see all the representatives and their forecasts. But if you are represtative you can see only your forecasts. 




