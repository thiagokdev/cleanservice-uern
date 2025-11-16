# Sistema CleanService - Estudo de Caso UERN

## 📋 Sobre o Projeto
Este projeto é um sistema corporativo simplificado desenvolvido como atividade avaliativa para a disciplina de **Desenvolvimento de Sistemas Corporativos** da UERN.

O sistema simula o controle de Ordens de Serviço (OS) de uma empresa de manutenção predial ("CleanService"), permitindo o cadastro e a consulta de serviços prestados.

## 🚀 Tecnologias Utilizadas
O projeto foi desenvolvido seguindo a arquitetura **MVC** (Model-View-Controller) e utiliza:

* **Back-end:** Java 17/21 com Spring Boot 3.
* **Persistência:** Spring Data JPA + Hibernate.
* **Banco de Dados:** MySQL 8.
* **Front-end:** HTML 5, CSS 3 e JavaScript (Vanilla).
* **Gerenciador de Dependências:** Maven.

## ⚙️ Pré-requisitos
Para executar este projeto, você precisa ter instalado:
1.  Java JDK 17 ou superior.
2.  MySQL Server 8.0.
3.  IDE Eclipse (ou similar).
4.  Maven.

## 🔧 Como Configurar e Rodar

### 1. Configuração do Banco de Dados
Antes de rodar a aplicação, crie um banco de dados no MySQL com o nome exato abaixo:

```sql
CREATE DATABASE cleanservice_db;