# SupportDesk

## 📌 Sobre o projeto

O **SupportDesk** é um sistema de gerenciamento de chamados técnicos desenvolvido em Java.
O objetivo do sistema é permitir que usuários registrem problemas ou solicitações de suporte, enquanto técnicos podem gerenciar, acompanhar e resolver esses chamados.

O sistema organiza os chamados por **status** e **prioridade**, facilitando o controle e a resolução das solicitações.

---

## ⚙️ Funcionalidades

* Cadastro de usuários
* Cadastro de técnicos
* Abertura de chamados
* Definição de prioridade do chamado
* Alteração de status do chamado
* Atribuição de técnicos aos chamados

---

## 🏗️ Arquitetura do projeto

O projeto segue uma arquitetura em camadas, separando responsabilidades para facilitar manutenção e organização do código.

src/main/java/com/supportdesk

controller → Camada responsável por receber requisições do sistema
service → Contém a lógica de negócio da aplicação
repository → Responsável pelo acesso aos dados
model → Representa as entidades do sistema
database → Configuração de conexão com o banco de dados

---

## 📦 Estrutura do projeto

```
SupportDesk
│
├── src
│   ├── main
│   │   ├── java/com/supportdesk
│   │   │   ├── controller
│   │   │   ├── service
│   │   │   ├── repository
│   │   │   ├── model
│   │   │   └── database
│   │   └── resources
│   │
│   └── test
│
├── pom.xml
└── README.md
```

---

## 🛠️ Tecnologias utilizadas

* Java
* Maven
* SQL Server
* JDBC

---

## 🗄️ Banco de dados

O sistema utiliza **SQL Server** para armazenamento dos dados.

Principais tabelas:

* Usuario
* Tecnico
* Chamado
* Status
* Prioridade
  
---

## 📚 Objetivo do projeto

Este projeto foi desenvolvido com fins educacionais para praticar:

* Programação orientada a objetos
* Organização de projetos Java
* Arquitetura em camadas
* Integração com banco de dados
* Boas práticas de desenvolvimento

