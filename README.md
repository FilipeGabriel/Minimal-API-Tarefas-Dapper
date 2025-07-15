# 📌 API de Tarefas - Minimal API com .NET 8

Este projeto é uma **Minimal API** desenvolvida com **.NET 8** que oferece operações CRUD para gerenciamento de tarefas, utilizando **Dapper.Contrib** para acesso ao banco de dados.

---

## 🚀 Funcionalidades

- ✅ Listar todas as tarefas
- ✅ Listar uma tarefa por ID
- ✅ Criar uma nova tarefa
- ✅ Atualizar uma tarefa existente
- ✅ Remover uma tarefa
- ✅ Endpoint de boas-vindas

---

## 🗂️ Endpoints

| Método | Rota                  | Descrição                        |
| ------ | --------------------- | -------------------------------- |
| GET    | `/`                   | Retorna mensagem de boas-vindas  |
| GET    | `/tarefas`            | Lista todas as tarefas           |
| GET    | `/tarefas/{id}`       | Retorna uma tarefa pelo ID       |
| POST   | `/tarefas`            | Cria uma nova tarefa             |
| PUT    | `/tarefas`            | Atualiza uma tarefa existente    |
| DELETE | `/tarefas/{id}`       | Remove uma tarefa pelo ID        |

---

## 🔧 Exemplo de Tarefa (JSON)

{ 
  "id": 1, 
  "nome": "Estudar .NET 8", 
  "isConcluida": false 
}

---

## 🛠️ Tecnologias e Bibliotecas

- [.NET 8](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- [Dapper.Contrib](https://github.com/DapperLib/Dapper.Contrib)
- [Swagger / Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)

---

## ▶️ Como Executar

1. **Clone o repositório:**

    git clone <URL-do-repositorio>

2. **Entre na pasta do projeto:**

    cd TarefasApi

3. **Execute a aplicação:**

    dotnet run

4. **Acesse o Swagger UI para explorar e testar os endpoints:**

    https://localhost:{porta}/swagger

---

## 🧩 Possíveis Melhorias

- Persistência com banco de dados real (ex: SQL Server, PostgreSQL)
- Implementar autenticação e autorização
- Adicionar testes unitários e de integração
- Implementar DTOs para entrada e saída de dados
- Aplicar padrões como Repository e Service Layer

---

## ❗ Observações

- Os dados persistidos dependem da configuração do banco de dados.
- O projeto utiliza Dapper.Contrib para operações simplificadas de CRUD.

---

## 🗃️ Recursos Adicionais

- [Documentação oficial do .NET Minimal APIs](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis)
- [Dapper](https://github.com/DapperLib/Dapper)
