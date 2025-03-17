# 📌 Sistema de Agendamento para Barbearia

## 💻 Sobre o Projeto
Este projeto tem como objetivo desenvolver um **sistema de agendamento** para uma barbearia, permitindo que clientes agendem horários de atendimento de forma prática e organizada. O backend foi desenvolvido com **Java e Spring Boot**, garantindo escalabilidade e segurança. 

Para a persistência de dados, utilizamos **JPA com Hibernate** e **PostgreSQL** como banco de dados relacional. O gerenciamento de versões do banco de dados é feito com **Flyway**, assegurando controle e organização das migrations.

## 🚀 Funcionalidades

✔️ Cadastro e gerenciamento de clientes

✔️ Agendamento de horários

✔️ Controle de disponibilidade dos barbeiros

✔️ Edição e cancelamento de agendamentos

✔️ Persistência de dados com PostgreSQL

✔️ Versionamento do banco de dados com Flyway

## 🏗️ Tecnologias Utilizadas
- **Java** (Spring Boot)
- **Spring Data JPA** (Hibernate)
- **PostgreSQL**
- **Flyway** (Controle de migrations)
- **Gradle** (Gerenciador de dependências)
- **Docker** (Opcional, para ambiente de desenvolvimento)

## 🔧 Como Executar o Projeto
### 📌 Pré-requisitos
Antes de rodar o projeto, certifique-se de ter instalado:
- **Java 17+**
- **PostgreSQL**
- **Gradle**
- **Docker** (opcional)

### 📥 Clonando o Repositório
```sh
 git clone https://github.com/pnascimentodev/barber-shop-api.git
 cd barbearia-agendamento
```

### 🔧 Configuração do Banco de Dados
1. Configure o PostgreSQL e crie um banco de dados com o nome desejado.
2. Atualize o `application.properties` ou `application.yml` com as credenciais do banco de dados.
3. O Flyway irá gerenciar as migrations automaticamente ao iniciar a aplicação.

### ▶️ Rodando a Aplicação
```sh
./gradlew bootRun
```
A aplicação estará disponível em `http://localhost:8080`.
