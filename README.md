# Projeto de Banco de Dados SistemaEs

Este repositório contém scripts SQL para a criação e manipulação de um banco de dados chamado `SistemaEs`. O banco de dados é utilizado para gerenciar informações sobre alunos, cursos e notas.

## Estrutura do Banco de Dados

1. **Excluir Banco de Dados Existente e Criar um Novo**
   ```sql
   DROP DATABASE IF EXISTS SistemaEs;
   SET SQL_SAFE_UPDATES = 0;
   CREATE DATABASE SistemaEs;
   USE SistemaEs;
