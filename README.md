# 🧠 TaskMaster API

Uma API RESTful simples para gerenciamento de tarefas (To-Do List), desenvolvida com Node.js, Express e MongoDB. Ideal para projetos pessoais, estudo de APIs REST e integração com front-ends diversos.

---

## 📦 Tecnologias Utilizadas

- **Node.js**
- **Express**
- **MongoDB + Mongoose**
- **JWT (JSON Web Token)** para autenticação
- **Dotenv** para variáveis de ambiente
- **Nodemon** (ambiente de desenvolvimento)

---

## 🚀 Funcionalidades

- ✅ Cadastro e login de usuários com autenticação JWT
- 📝 CRUD completo de tarefas:
  - Criar
  - Listar
  - Atualizar
  - Deletar
- 🔐 Proteção de rotas com autenticação
- 🔎 Filtros por status (pendente, em andamento, concluída)

---

| Método | Rota           | Descrição                  | Autenticado? |
| ------ | -------------- | -------------------------- | ------------ |
| POST   | /auth/register | Criação de novo usuário    | ❌            |
| POST   | /auth/login    | Login do usuário           | ❌            |
| GET    | /tasks         | Listar todas as tarefas    | ✅            |
| POST   | /tasks         | Criar uma nova tarefa      | ✅            |
| PUT    | /tasks/\:id    | Atualizar tarefa existente | ✅            |
| DELETE | /tasks/\:id    | Deletar uma tarefa         | ✅            |

