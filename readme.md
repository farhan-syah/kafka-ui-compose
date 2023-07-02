## About

A compose file to run kafka cluster & kafka UI without zookeper locally.

# Run kafka

```sh
docker compose -f kafka.yml up
```

# Run kafka in detached mode

```sh
docker compose -f kafka.yml up -d
```

# Access Kafka UI

If you don't change the port number, it will be running on

```sh
localhost:8800
```
