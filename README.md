create application - npx express-generator express-crud --hbs
run express appliation - npm run dev and config in package.json with nodemon

#setup application 

configure Mongoose ( Dependencies - mongoose, dotenv, bodyparser, method-override)
Models (Books)

app.use(methodOverride('_method')) #to Support http methods which are more than GET && POST

Configure Router (indexRouter, booksRouter)
CRUD books