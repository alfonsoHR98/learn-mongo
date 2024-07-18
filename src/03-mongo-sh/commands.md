## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "URL"
```

```sh
show dbs
show collections
```

```sh
use("MongoLearn")
db.products.find()
```