# Kafka Dockerlab
The main objective of creating this lab was to provide Simple hands-on lab for the people who are willing to learn about Kafka and its monitoring aspect. So we can say this is a Dockerized Example of **[Apache Kafka](https://kafka.apache.org/)**, **[Prometheus](https://prometheus.io/)** and **[Grafana](https://grafana.com/)**.

## Requirments
We don't have a long list of requirments but yes we do have some of them. The need for running this setup is:-
- [X] Docker
- [X] Docker Compose

## Pre-Requisites
The only pre-requisite is:-
- set `KAFKA_ADVERTISED_HOST_NAME` in `docker-compose.yml` to match your docker host IP. (Note: Do not use localhost or 127.0.0.1 as the host ip if you want to run multiple brokers).
