# Midnight Node Docker

This allows for easy orchestration of the Midnight Node service.

## System requirements

- Install [Docker-Compose](https://docs.docker.com/compose/install/)

## Usage

1. Clone repo

3. Modify values in `.env` file as applicable 

2. Navigate to .yml file and `docker-compose up`

```shell
docker-compose up -d
```

or for both Midnight and Cardano:

```shell
docker-compose -f ./compose-partner-chains.yml -f ./compose.yml up -d
```

🚀 That's it.
