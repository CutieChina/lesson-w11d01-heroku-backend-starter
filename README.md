# Backend NOtes

https://devcenter.heroku.com/articles/getting-started-with-nodejs?singlepage=true

`config/config/json`

```js
{
  "development": {
    "database": "project3-backend-test-development",
    "host": "127.0.0.1",
    "dialect": "postgres"
  },
  "production": {
    "database": "project3-backend-test-production",
    "use_env_variable": "DATABASE_URL",
    "dialect": "postgres"
  }
}
```


heroku run bash

sequelize db:migrate

https://project3-backend-test.herokuapp.com/users

app.use(cors())
nodemon
https://gist.github.com/vapurrmaid/a111bf3fc0224751cb2f76532aac2465

## Connect Heroku DB to PG Admin

## Frontend

axios