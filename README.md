
# Quiz Application

A cutting-edge quiz application that seamlessly combines Next.js for the frontend, Prisma for the backend, and Tailwind CSS for styling, all driven by TypeScript.




## Installation


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`DATABASE_URL`

`NEXTAUTH_SECRET`


## Run Locally

Clone the project

```bash
  git clone https://github.com/acharyaprakash30/quizi-mate.git
```

Go to the project directory

```bash
  cd quizi-mate
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm start
```


this project uses shadcn to make buttons and all other stuff . the benifit of using shadcn is This is NOT a component library. It's a collection of re-usable components that you can copy and paste into your apps.

setup backend
1. install prisma : npm i --save-dev prisma
2. install prisma client to interact:  npm i @prisma/client 
3.npx prisma init --datasource-provider sqlite  //for init of prisma and sqlite database configuration

Note:
the lib folder created just to define the new library using or prepare some configuration before use .for prisma configuration we create db.ts inside lib folder
4. create all the required model 
5. push database or migrate using npx prisma db push

//setup the authentication using next-auth
1.npm install next-auth
now for configuration of next auth  in lib folder create nextauth.ts
for prisma using in nextjs install next-auth prisma adapter using command
2.npm i @next-auth/prisma-adapter



















#