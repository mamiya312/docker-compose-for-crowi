# Crowi on docker-compose

## run

```
$ git clone https://github.com/mamiya312/docker-compose-for-crowi.git crowi
$ cd crowi
$ cp .env.sample .env
$ vi .env  # Edit PASSWORD_SEED
$ docker-compose up -d
```

## update
```
$ docker-compose stop
$ docker-compose rm
$ docker-compose up -d
```
