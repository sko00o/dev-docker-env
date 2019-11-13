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

- MySQL: `root:toor@tcp(localhost:13306)/demo_test?parseTime=True`
- Postgres: `dbname=demo_test user=root password=toor port=15432 sslmode=disable`

## Redis

URL:

`redis://localhost:16379/1`

## MQTT

SCHEME:

`tcp://localhost:11883`

