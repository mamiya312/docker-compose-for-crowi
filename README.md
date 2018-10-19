# Crowi on docker-compose

## run

```
$ git clone --recursive https://github.com/mamiya312/docker-compose-for-crowi.git crowi
$ cd crowi
$ vi docker-compose.yml  # Edit PASSWORD_SEED
$ docker-compose up -d
```

## update
```
$ docker-compose stop
$ docker-compose rm
$ docker-compose build
$ docker-compose up -d
```
