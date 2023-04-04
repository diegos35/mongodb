## Connect to container

```sh
docker-compose exec mongodb bash
```


##Connect with mongosh

```sh
mongosh "url local de docker o atlas cloud"
sin necesdiad de entrar al bash
docker compose exec mongodb mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

```sh
show dbs
show collections
```


```sh
use("platzi_store")
db.products.find({})    
```