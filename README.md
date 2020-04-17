# Dockerized RoR application

[![Build Status](https://travis-ci.org/markkorput/pyevento.svg)](https://travis-ci.org/markkorput/ror_docker_auth.svg)

# Start Servers

***Start postgresql db and rails app docker containers***
```bash
docker-compose up [--build]
```

***Create DB***
```bash
docker-compose exec app rails db:create
```

# Stop Servers

```bash
docker-compose down
```

