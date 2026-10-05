# Solicita — Infraestrutura

Repositório responsável pela execução da infraestrutura da aplicação Solicita.

## Pré-requisitos

- Docker
- Docker Compose

## Execução

Clone este repositório:

```bash
git clone https://github.com/DovCaio/solicita-infra.git
cd solicita-infra
```

## Iniciar os serviços

```bash
docker compose up -d
```

## Arquitetura

A aplicação é composta por três serviços:

- **Frontend:** aplicação web desenvolvida com Next.js.
- **Backend:** API REST desenvolvida com Spring Boot.
- **PostgreSQL:** banco de dados utilizado pela aplicação.

As imagens do frontend e backend são publicadas no Docker Hub e consumidas pelo `docker-compose.yml`.
