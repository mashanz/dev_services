# LOCAL SERVICE

Copy `.env.example` to `.env` and run `docker-compose up -d`

## Services Lists

- PostgreSQL
  - pg-master `localhost:54321`
  - pg-slave `localhost:54322`
- Redis Stack
  - redis-server: `localhost:6379`
  - redis-insigth: `localhost:8001`
- mongo
  - mongo: `localhost:27017`
  - mongo-express: `localhost:8081`
- rabbitmq
  - rabbitmq: `localhost:5672`
  - rabbitmq-management: `localhost:15672`
- minio
  - minio: `localhost:9000`
  - minio-service: `localhost:9001`
- meilisearch
  - meilisearch: `localhost:7700`
- vault
  - vault: `localhost:8200`
