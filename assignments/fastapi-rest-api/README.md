# 📘 Assignment: Construindo APIs REST com FastAPI

## 🎯 Objective

Aprender a criar uma API REST simples utilizando o framework FastAPI em Python. O estudante irá construir uma aplicação CRUD para gerenciar uma lista de tarefas (to-do list).

## 📝 Tasks

### 🛠️ Criar estrutura básica do projeto FastAPI

#### Description
Inicialize um novo projeto Python e instale o FastAPI e o Uvicorn. Crie o arquivo principal da aplicação (`main.py`).

#### Requirements
Completed program should:

- Ter um ambiente Python configurado
- Ter FastAPI e Uvicorn instalados
- Conter um arquivo `main.py` com uma aplicação FastAPI mínima


### 🛠️ Implementar endpoints CRUD para tarefas

#### Description
Implemente endpoints para criar, listar, atualizar e remover tarefas da lista. Cada tarefa deve conter um id, título e status (concluída ou não).

#### Requirements
Completed program should:

- Permitir adicionar uma nova tarefa via POST
- Permitir listar todas as tarefas via GET
- Permitir atualizar o status ou título de uma tarefa via PUT
- Permitir remover uma tarefa via DELETE


### 🛠️ Testar a API com o Swagger UI

#### Description
Utilize a interface automática do FastAPI (Swagger UI) para testar todos os endpoints criados.

#### Requirements
Completed program should:

- Acessar a documentação interativa em `/docs`
- Testar todos os endpoints diretamente pela interface
- Corrigir eventuais erros encontrados nos testes

