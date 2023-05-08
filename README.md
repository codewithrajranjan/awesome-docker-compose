### Motive Behind this project

 Every time you want to work on new product then you have spend much time in setting up those services on your local machine.
Also the installation step is different for each operating system. 
This project aims to solve this problem where common product ecosystem can be easily installed on any operating system.

### How to Start the services

- clone the repository
- search for the docker-compose that you want to run
- If it contains Configuration section then modify the docker-compose file with suitable configuration value.
- If you are familiar with docker compose file then you can modify the settings in docker-compose file or run with the default values
- Run the services in foreground mode

```bash
    docker-compose -f <file-name> up 
```

- or Run the services in background mode

```bash
    docker-compose -f <file-name> up -d
```

### List of services or ecosystem

-----------------------------------------

> [Kafka Zookeeper KafkaManager Ecosystem](https://github.com/self-tuts/awesome-docker-compose/blob/master/ecosystem/kafka-zookeeper-kafkamanager-docker-compose.yml)

- Configuration
  - **[machine-ip-address]** : provide the ip-address of the machine.

> [Elasticsearch Kibana Ecosystem](https://github.com/self-tuts/awesome-docker-compose/blob/master/ecosystem/elasticsearch-kibana-docker-compose.yml)


> [MySQL Service](https://github.com/self-tuts/awesome-docker-compose/blob/master/mysql/mysql-5.7-docker-compose.yml)

> [RabbitMQ](https://github.com/self-tuts/awesome-docker-compose/blob/master/rabbitmq/rabbitmq-docker-compose.yml)

> [Docker Registry](https://github.com/self-tuts/awesome-docker-compose/blob/master/docker-registry/docker-registry-compose.yml)

> [Redis Standalone](https://github.com/self-tuts/awesome-docker-compose/blob/master/redis/redis-docker-compose.yml)

- In redis insight use the host ip address

> [Postgres](https://github.com/self-tuts/awesome-docker-compose/blob/master/database/postgres.postgres.yml)
