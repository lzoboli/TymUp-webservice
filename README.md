# TymUp Webservice

Repositório criado para o desenvolvimento do webservice **TymUp** para a matéria de **Programação Web II**.

## Tecnologias Utilizadas

* **Java** (17+)
* **Spring Boot** (Web, Data JPA)
* **Maven** (Gerenciamento de dependências e build)
* **PostgreSQL** (Banco de dados relacional)
* **Docker & Docker Compose** (Containerização do banco de dados)

## Pré-requisitos

* [JDK 17](https://adoptium.net/) ou superior
* [Docker](https://www.docker.com/) e Docker Compose instalados
* [Git](https://git-scm.com/)

## Como Executar

### 1. Subir o banco de dados
Na raiz do projeto, inicie o container do banco de dados utilizando o Docker Compose:
```bash
docker-compose up -d
