# 🏢 Sistema CleanService - Estudo de Caso UERN

## 📋 Sobre o Projeto
Este projeto é um sistema corporativo simplificado desenvolvido como atividade avaliativa para a disciplina de **Desenvolvimento de Sistemas Corporativos** da UERN.

O sistema simula o controle de Ordens de Serviço (OS) de uma empresa de manutenção predial ("CleanService"), atendendo integralmente aos requisitos de Autenticação, Transação, Persistência e Relatórios.

## 🚀 Tecnologias Utilizadas
* **Linguagem:** Java (JDK 17/21)
* **Framework:** Spring Boot 3
* **Banco de Dados:** MySQL 8
* **Front-end:** HTML 5, CSS 3 e JavaScript
* **Gerenciador:** Maven

---

## 🔐 ACESSO AO SISTEMA (Login)
O sistema possui uma camada de segurança. Utilize as credenciais abaixo para acessar:

| Usuário | Senha |
| :--- | :--- |
| **admin** | **123** |

---

## ⚙️ MANUAL DE INSTALAÇÃO E EXECUÇÃO

Siga os passos abaixo para rodar o projeto em sua máquina local.

### 1. Configuração do Banco de Dados
O sistema utiliza o Hibernate para criar as tabelas automaticamente. Você só precisa criar o banco vazio.
Abra seu MySQL (Workbench ou Terminal) e execute:

```sql
CREATE DATABASE cleanservice_db;

#### 2. Configuração de Credenciais
O projeto espera que seu MySQL utilize as credenciais padrões de ambiente acadêmico:

Usuário: root

Senha: 123456

Caso sua senha seja diferente, edite o arquivo src/main/resources/application.properties antes de rodar.

### 3. Execução no Eclipse
Importe o projeto como Existing Maven Project.

Navegue até a classe principal: src/main/java/br/com/cleanservice/cleanservice/CleanserviceApplication.java.

Clique com o botão direito no arquivo e selecione Run As > Java Application.

Aguarde a mensagem no console: Tomcat started on port(s): 8081.

### 4. Acessando a Aplicação
Com o servidor rodando, abra seu navegador e acesse o link:

👉 http://localhost:8081/index.html

✅ Funcionalidades Implementadas
Autenticação: Tela de bloqueio inicial.

Cadastro (Transação): Registro de Clientes, Serviços e Valores no banco.

Persistência: Conexão direta com MySQL via JPA.

Relatórios: Listagem e atualização automática das OS cadastradas.

Aluno: THIAGO LOPES DA SILVA Curso: Sistemas para Internet - UERN
