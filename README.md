# Postgres DB in docker

## Attention
Makefile configured for docker compose (golang) plugin.

To run with docker-compose (python),
you need to replace "docker compose" with "docker-compose" in Makefile.

## How to
```bash
# docker run
make init
```

```bash
# docker stop
make down
```

```bash
# docker stop with clean data
make down-clear
```

## Access
### Root (postgres DB)
```
user:       postgres
password:   postgres
db:         postgres
port:       5432
```

### App (my_app DB)
```
user:       app
password:   password
db:         my_app
port:       5432
```
