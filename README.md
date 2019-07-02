# PHP in Docker

set up nginx + php + mysql environment in docker

## Required

- docker
- docker-compose

setting `/etc/hosts`:

```hosts
127.0.0.1 php-docker.test
```

## How to run

start service:

```bash
$ docker-compose up -d
```

stop service:

```bash
$ docker-compose stop
```

### test url

- nginx index: http://localhost:8080/
- php index: http://php-docker.test:8080/
- php info: http://php-docker.test:8080/info.php
- adminer index: http://php-docker.test:8888/
