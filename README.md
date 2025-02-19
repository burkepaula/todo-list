# API To Do List

Esta API permite gerenciar uma lista de tarefas.

## Funcionalidades:

*   Criar novas tarefas (`POST /api/tasks`).
*   Obter todas as tarefas (`GET /api/tasks`).
*   Obter uma tarefa específica (`GET /api/tasks/{id}`).
*   Atualizar uma tarefa (`PUT /api/tasks/{id}`).
*   Excluir uma tarefa (`DELETE /api/tasks/{id}`).

## Como Executar:

1. Pré-requisitos: Java 21, Maven.
2. Clonar o repositório: `git clone <[https://github.com/burkepaula/todo-list]>`
2. Construir o projeto: `mvn clean install`
3. Executar a aplicação: `mvn spring-boot:run`
4. Testar a API: Use o Postman ou uma ferramenta similar para testar os endpoints.
5. Testes unitários e de integração: Os testes estão incluídos no projeto, execute usando `mvn test`

## Tecnologias:

* Java 21
* Maven
* Spring Boot
* Spring Data JPA
* H2 Database
* JUnit 5
* Mockito
* AssertJ

## Autor:

Paula Burke
