# Comandos utilizados no terminal

Neste arquivo pode-se encontrar os comandos frequentemente utilizados ao longo do projeto no terminal.
Gosto de deixar anotado porque sempre acabo me esquecendo desses comandos futuramente kk

## Subindo o ambiente

```bash
docker-compose up -d
```

## Podemos entrar dentro do nosso container kafka, utilizando o seguinte comando

```bash
docker exec -it fs-kafka_course_kafka_1 bash
```

## Inicializando modulo Go

go mod init github.com/vitor9/fs-gokafka

## Rodando o main da app

go run cmd/producer/main.go

