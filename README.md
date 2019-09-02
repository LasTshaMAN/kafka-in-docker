# Kafka-In-Docker

This project demonstrates how one can easily deploy Kafka in Docker.

## Deployment 

### Mac OS

Run the following script (from this repo):
```shell script
KAFKA_ADVERTISED_HOST_NAME=$(ipconfig getifaddr en0) docker-compose -f ./docker/docker-compose.yml up
```