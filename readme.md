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
