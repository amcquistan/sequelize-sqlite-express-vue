# sequelize-sqlite-express-vue

A silly toy contacts management application that I used in my [StackAbuse](stackabuse.com) blog article [Using Sequelize.js and SQLite in an Express.js App](http://stackabuse.com/using-sequelize-js-and-sqlite-in-an-express-js-app/) demonstrating how to use Vue.js, Node.js, Express.js and sequelize.js in combination with a SQLite database.

## Usage

1) Clone repo

```sh
git clone https://github.com/amcquistan/sequelize-sqlite-express-vue.git
```

2) install dependencies (Built with Node.js version 8.10)

```sh
cd sequelize-sqlite-express-vue/
npm install
```

3) run migrations and seeders

```sh
node_modules/.bin/sequelize db:migrate
node_modules/.bin/sequelize db:seed:all
```

4) start express server

```sh
npm start
```
