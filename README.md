# Backend - Sistema de Lista de Tarefas

Este é o repositório do backend do Sistema de Lista de Tarefas do Curso de Tecnologia Online. O backend é responsável por fornecer os serviços de API para gerenciamento de tarefas.

## Índice

1. [Sobre o Projeto](#sobre-o-projeto)
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)
3. [Configuração do Ambiente de Desenvolvimento](#configuração-do-ambiente-de-desenvolvimento)
4. [Como Rodar](#como-rodar)
5. [Endpoints da API](#endpoints-da-api)
6. [Contribuição](#contribuição)
7. [Licença](#licença)

## Sobre o Projeto

O backend do Sistema de Lista de Tarefas é construído em .NET Core e fornece uma API RESTful para realizar operações CRUD (Create, Read, Update, Delete) nas tarefas. Utiliza um banco de dados PostgreSQL para persistência dos dados.

## Tecnologias Utilizadas

- .NET Core
- PostgreSQL

## Configuração do Ambiente de Desenvolvimento

1. Certifique-se de ter o SDK do .NET Core e o PostgreSQL instalados na sua máquina.
2. Clone este repositório.

## Como Rodar

1. Configure a conexão com o banco de dados no arquivo `appsettings.json`.
2. Execute o comando `dotnet run` no terminal para iniciar o servidor.

## Endpoints da API

- `/api/tarefas`: 
  - GET: Retorna todas as tarefas.
  - POST: Adiciona uma nova tarefa.
- `/api/tarefas/{id}`:
  - GET: Retorna uma tarefa específica.
  - PUT: Atualiza uma tarefa existente.
  - DELETE: Exclui uma tarefa.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request com melhorias, correções ou novas funcionalidades.

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.
