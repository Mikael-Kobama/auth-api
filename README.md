# Authentication API

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

Este projeto é uma **API de Autenticação e Autorização** desenvolvida com **Java** e **Spring Boot**. O objetivo principal é fornecer uma base sólida para a gestão de usuários, utilizando tecnologias modernas e as melhores práticas de segurança.

A API foi construída por **Mikael Kobama** como um projeto de estudo e portfólio, com base em um tutorial de [Fernanda Kipper](https://github.com/Fernanda-Kipper).

---

## Recursos e Tecnologias

Este projeto foi construído com as seguintes ferramentas e conceitos para garantir uma solução segura e escalável:

* **Spring Boot**: Framework principal para o desenvolvimento rápido da API.
* **Spring Security**: Módulo de segurança robusto para autenticação e controle de acesso.
* **JWT (JSON Web Tokens)**: Implementado para autenticação stateless, garantindo que o servidor não precise armazenar o estado das sessões.
* **PostgreSQL**: Banco de dados relacional utilizado para persistência dos dados.
* **Flyway**: Ferramenta de versionamento de banco de dados para gerenciar migrações de schema de forma automática e segura.

---

## Como Rodar o Projeto

Siga os passos abaixo para configurar e executar a aplicação em sua máquina local.

### Pré-requisitos
* Java 17+
* Docker (para o banco de dados)
* Maven

### 1. Clonar o Repositório

```bash
git clone [https://github.com/SeuUsuario/NomeDoSeuRepositorio.git](https://github.com/SeuUsuario/NomeDoSeuRepositorio.git)
