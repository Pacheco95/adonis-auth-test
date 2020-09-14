# Steps to reproduce the project
```
npm init adonis-ts-app adonis-auth-test --eslint true --boilerplate api
cd adonis-auth-test
npm start
npm i @adonisjs/lucid@alpha
node ace invoke @adonisjs/lucid
mkdir temp
npm i @adonisjs/auth@alpha
node ace invoke @adonisjs/auth
node ace migration:run
npm i @adonisjs/session
node ace make:controller Auth (add code to routes and auth controller accordingly with the docs)
npm i phc-argon2
```
