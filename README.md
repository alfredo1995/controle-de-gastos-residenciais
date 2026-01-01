# Controle de Gastos Residenciais

Sistema completo para controle de receitas, despesas e saldo de moradores de uma residência. Este projeto foi desenvolvido como trabalho acadêmico e integra front-end em React (Next.js + TypeScript) com back-end em ASP.NET Core (C#), utilizando armazenamento em memória.

## Estrutura do Projeto

O repositório contém dois diretórios principais:

- `/controle-gastos-front` → Front-end com React + Next.js + TypeScript
- `/ControleGastosAPI` → Back-end com ASP.NET Core (C#)

---

## Funcionalidades

- Cadastro, exclusão e listagem de pessoas
- Cadastro, edição e exclusão de transações (receitas ou despesas)
- Validação de idade mínima para registrar receitas
- Resumo de transações por pessoa
- Totais gerais (receita, despesa, saldo)
- Interface moderna, responsiva e fácil de usar

---

## Tecnologias Utilizadas

### Backend
- ASP.NET Core
- C#
- Armazenamento em memória (sem banco de dados)

### Frontend
- React
- Next.js
- TypeScript
- Axios
- CSS Global com estilização moderna

---

## Como Rodar o Projeto

### 1. Clonar o Repositório

bash
            
      git clone https://github.com/alfredo1995/controle-de-gastos-residenciais.git
      cd controle-de-gastos-residenciais

Instalar os pré-requisitos

    Git
    Node.js (com npm)
    .NET SDK (ASP.NET Core)

Rodar o back-end (API)

    cd ControleGastosAPI
    dotnet restore
    dotnet run

    A API será iniciada em http://localhost:5275.

Rodar o front-end

    cd controle-gastos-front
    npm install
    npm run dev

    O front-end ficará disponível em http://localhost:3000.

Acessar a aplicação

    Abra o navegador e acesse http://localhost:3000
    O front-end se comunicará com a API em memória



