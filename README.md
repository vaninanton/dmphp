```shell
docker compose up -d
```

Открыть http://localhost:8080

В IDE настроить xdebug на прослушку порта 9003
Поставить брейкпоинт и смотреть логи в docker:
```shell
docker compose logs -f
```