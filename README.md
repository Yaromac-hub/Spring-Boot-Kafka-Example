# Kafka - Spring Boot - PostgreSQL


This project provides a real-world example of using Spring Boot and Kafka. It is a multi-module Maven project. Inspired by Ramesh Fadatare (Java Guides)

## kafka-producer

The `kafka-producer` module reads events from https://stream.wikimedia.org/v2/stream/recentchange and produces messages to Kafka. To set up Kafka, simply run the relevant docker-compose.yml file in the sources folder of this submodule.

## kafka-consumer

The `kafka-consumer` module reads messages from Kafka and sends them to PostgreSQL. To set up PostgreSQL, run the relevant docker-compose.yml file in the sources folder of this submodule. For reference on setting up PostgreSQL using docker-compose, please see [here](https://github.com/khezen/compose-postgres/pull/23/files).
