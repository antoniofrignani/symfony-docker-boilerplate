### Getting started

```bash
docker-compose up --build
```

To access directly from local host the PostgreSQL database container

```bash
psql postgresql://postgres:password@127.0.0.1:15432/dbtest
```

To access php-fpm terminal
```
docker-compose exec php-fpm bash
```
