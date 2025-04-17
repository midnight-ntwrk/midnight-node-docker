 📦 This Repository is Archived

**Note:** This project is no longer maintained here.

🚀 It has moved to a new home:
👉 [**github.com/midnightntwrk/midnight-node-docker**](https://github.com/midnightntwrk/midnight-node-docker)

(note the lack of a hyphen in the org name)

Please update your bookmarks and head over there for the latest updates!

# Midnight Node Docker:

This allowed for easy orchestration of the Midnight Node service.

## System requirements

- Install [Docker-Compose](https://docs.docker.com/compose/install/)

## Usage

1. Clone repo

3. Modify values in `.env` file as applicable 

2. Navigate to .yml file and `docker-compose up`

```shell
DOCKER_DEFAULT_PLATFORM=linux/amd64 docker-compose up -d
```

or for both Midnight and Cardano:

```shell
DOCKER_DEFAULT_PLATFORM=linux/amd64 docker-compose -f ./compose-partner-chains.yml -f ./compose.yml up -d
```

or for Midnight, Cardano and a local Proof Server:

```shell
DOCKER_DEFAULT_PLATFORM=linux/amd64 docker-compose -f ./compose-partner-chains.yml -f ./compose.yml -f ./proof-server.yml up -d
```

🚀 That's it.

----

 📦 This Repository is Archived

**Note:** This project is no longer maintained here.

🚀 It has moved to a new home:
👉 [**github.com/midnightntwrk/midnight-node-docker**](https://github.com/midnightntwrk/midnight-node-docker)

(note the lack of a hyphen in the org name)

Please update your bookmarks and head over there for the latest updates!
