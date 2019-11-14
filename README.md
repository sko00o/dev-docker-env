# dev-env-docker

## Usage

```sh
docker-compose up -d
```

start kafka

```sh
docker-compose -f kafka-zk-single.yml up -d
```

## Database

DSN:

- MySQL8.0: `root:toor@tcp(localhost:13306)/demo_test?parseTime=True`
- MySQL5.7: `root:toor@tcp(localhost:13307)/demo_test?parseTime=True`
- Postgres9.6: `dbname=demo_test user=root password=toor port=15432 sslmode=disable`


## Redis

URL:

`redis://localhost:16379/1`

## MQTT

SCHEME:

`tcp://localhost:11883`

## Kafka

`localhost:9092`

## Zookeeper

`localhost:2181`


