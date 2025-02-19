# express-learn

create .env file in root directory with the information from mongodb database url for a mongoose driver connection
```env
DATABASE_URL="mongodb+srv://<username>:<password>@<clustername>"
```

```shell
node populatedb.js "mongodb url"
```

To start the app:
```shell
npm start
```

### The URLs

http://localhost:3000/
http://localhost:3000/catalog
http://localhost:3000/catalog/books
http://localhost:3000/catalog/bookinstances/
http://localhost:3000/catalog/authors/
http://localhost:3000/catalog/genres/
http://localhost:3000/catalog/book/5846437593935e2f8c2aa226
http://localhost:3000/catalog/book/create
