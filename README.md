# API de Agendamento de Horários

Projeto backend desenvolvido com **Java** e **Spring Boot** para gerenciamento de agendamentos e horários.

A aplicação foi estruturada em camadas, seguindo boas práticas de organização de código e separação de responsabilidades, com o objetivo de simular um fluxo de agendamento no backend e reforçar conceitos importantes de desenvolvimento com Spring Boot.

---

## Objetivo do projeto

Este projeto foi desenvolvido com foco em praticar a construção de uma aplicação backend utilizando:

- Java
- Spring Boot
- arquitetura em camadas
- persistência de dados
- organização de código
- separação entre regras de negócio e acesso a dados

---

## Funcionalidades

- cadastro de agendamentos
- listagem de agendamentos
- gerenciamento de horários
- persistência de dados
- estrutura organizada em camadas

---

## Estrutura do projeto

A aplicação segue a seguinte organização:

- **Controller** → recebe as requisições da API
- **Service** → contém a lógica de negócio
- **Repository** → responsável pela comunicação com o banco de dados
- **Entity** → representa os dados da aplicação

---

## Tecnologias utilizadas

- **Java**
- **Spring Boot**
- **Spring Data JPA**
- **Maven**
- **Banco de Dados H2**
- **Git / GitHub**

---

## Conceitos aplicados

- desenvolvimento de APIs REST
- arquitetura em camadas
- persistência de dados
- separação de responsabilidades
- organização de código
- boas práticas de desenvolvimento backend

---

## Como executar o projeto

### Pré-requisitos

- Java instalado
- Maven instalado
- IDE de sua preferência (IntelliJ IDEA, VS Code, Eclipse)

### Passos

1. Clone este repositório:

git clone https://github.com/pedroppaf/agenda-horarios.git

2. Acesse a pasta do projeto:

cd agenda-horarios

3. Execute a aplicação com Maven:

mvn spring-boot:run
