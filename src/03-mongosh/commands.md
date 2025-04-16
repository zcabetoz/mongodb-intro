## connect to container
```sh
docker-compose exec mongo bash
```
## contect with mongosh
```sh
mongosh ""
```

```sh
show dbs
show colletions
```

```sh
use('payall')
db.User.find({username:'nayarit'})
```