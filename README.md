# To-do API 📋

## Sobre o Projeto

API REST de gerenciamento de tarefas desenvolvida com **Spring Boot**.

## Funcionalidades
- Cadastro de usuários
- CRUD de tarefas (To-do)

## Detalhes do Projeto
- Autenticação via Basic Authentication
- Documentação da API com Swagger
- Testes unitários utilizando **JUnit** e **Mockito**.
  
### Usuário

| Método | Rota             | Descrição              |
| ------ | ---------------- | ---------------------- |
| POST   | `/auth/register` | Cadastrar novo usuário |

### To-Do

| Método | Rota              | Descrição                    |
| ------ | ----------------- | ---------------------------- |
| POST   | `/todo`           | Criar tarefa                 |
| GET    | `/todo`           | Listar tarefas               |
| PUT    | `/todo/{id}`      | Atualizar tarefa             |
| PUT    | `/todo/{id}/done` | Alternar status de conclusão |
| DELETE | `/todo/{id}`      | Deletar tarefa               |


---

Feito por [Gabriel Venancio de Avelar](https://github.com/gabrielvavelar).


