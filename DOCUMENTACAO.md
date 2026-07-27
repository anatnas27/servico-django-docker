# Documentação do Projeto

## Descrição

Este projeto consiste em um serviço web desenvolvido utilizando Django e executado através de containers Docker.

## Tecnologias utilizadas

- Python
- Django
- Docker
- Docker Compose
- SQLite

## Estrutura do projeto

- catalogo: aplicação Django responsável pelo catálogo de filmes.
- core: configurações principais do projeto.
- Dockerfile: configuração da imagem Docker.
- docker-compose.yml: configuração do serviço.

## Execução

Para iniciar a aplicação:

docker compose up --build

A aplicação estará disponível em:

http://localhost:8000

## Banco de dados

O projeto utiliza SQLite através do arquivo db.sqlite3.

## Controle de versão

O desenvolvimento foi organizado utilizando Git e GitHub com branch de documentação e commits versionados.