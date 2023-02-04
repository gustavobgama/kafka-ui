# Introduction

This is a setup to run [kafka-ui](https://github.com/provectus/kafka-ui), a simple and useful kafka client in docker using docker-compose.

# Usage

Pre requisites, must be installed:

* [docker](https://docs.docker.com/install/)
* [docker-compose](https://docs.docker.com/compose/install/)

## Start

```bash
$ cp .env.example .env
// configure the .env file
$ docker-compose up -d
```

The kafka ui web interface is available at [http://localhost:8080](http://localhost:8080).

## Stop

```bash
$ docker-compose down
```