## Docker

Die Anwendung kann als Docker-Container gebaut und gestartet werden:

```sh
docker compose -f docker/docker-compose.yml up --build
```

Danach ist die App unter <http://localhost:8080> erreichbar.

Zum Stoppen:

```sh
docker compose -f docker/docker-compose.yml down
```
