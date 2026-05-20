### Hexlet tests and linter status:
[![Actions Status](https://github.com/andrewostt/docker-project-74/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/andrewostt/docker-project-74/actions)

### CI status:
[![CI](https://github.com/andrewostt/docker-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/andrewostt/docker-project-74/actions/workflows/push.yml)

## JS Fastify Blog

Блог на [Fastify](https://fastify.dev/), упакованный в Docker. Docker Hub образ: [andrewostt/docker-project-74](https://hub.docker.com/r/andrewostt/docker-project-74).

## Требования

- Docker >= 20.10
- Docker Compose >= 2.0

## Установка

```bash
# Скопировать файл с переменными окружения
cp .env.example .env

# Установить зависимости и выполнить миграции
make setup
```

## Запуск

```bash
# Запустить приложение (доступно на https://localhost)
make dev

# Остановить
make down
```

## Тесты

```bash
# Запустить тесты через Docker Compose
make test
```
