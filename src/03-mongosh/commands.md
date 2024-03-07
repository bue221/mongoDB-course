## Connect to docker container

```sh
docker-compose  exec mongodb bash
```

## Connect wuth mongosh

```sh
mongosh "mongodb://root:*****@localhost:27017/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```
