
Need to add config *.env* file with secure settings( database connection, secret salt etc.)

Short sample *.env* file

```
DEBUG='False'
MONGO_HOST='mongodb://user:pass@mongo_host:mongo_port/mongo_database'
MONGO_DB_NAME='mongo_database'
SECRET_KEY='some secure key'
HOST='127.0.0.1'
PORT=8000
```

To run server

```
./app.py
```
