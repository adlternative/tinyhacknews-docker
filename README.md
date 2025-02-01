# tinyhacknews-docker

used for start tinyhacknews WEB.

### build

```sh
docker-compose --env-file .env.dev -f docker-compose.dev.yml up --build  -d
```

### stop

```sh
docker-compose --env-file .env.dev -f docker-compose.dev.yml down
```