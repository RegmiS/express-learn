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