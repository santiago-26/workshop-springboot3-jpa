# Projeto: Web Services com Spring Boot e JPA

Este projeto é uma API RESTful desenvolvida em Java com Spring Boot, JPA/Hibernate e banco de dados H2/PostgreSQL, com foco em operações CRUD, relacionamentos entre entidades e boas práticas de estruturação em camadas.

## 🚀 Funcionalidades

- Cadastro de usuários, produtos, categorias e pedidos
- CRUD completo com tratamento de exceções
- Relacionamentos entre entidades:
  - One-to-Many, Many-to-Many, One-to-One
- Camadas organizadas em:
  - Resource, Service e Repository
- Uso de banco de dados em memória (H2) e PostgreSQL
- Preparado para deploy em nuvem (ex: AWS)

## 🛠 Tecnologias

- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database (testes locais)
- PostgreSQL (produção)
- Maven
- AWS (deploy em nuvem)

## 🧱 Estrutura do Projeto


```

📁 src
┣ 📂 entities
┣ 📂 repositories
┣ 📂 resources
┣ 📂 services
┣ 📂 config
┗ 📜 application.properties

````

## 🔧 Como executar localmente

1. Clone o repositório:
```bash
git clone https://github.com/santiago-26/santiago-26.git
````

2. Acesse a pasta do projeto:

```bash
cd santiago-26
```

3. Execute a aplicação:

```bash
./mvnw spring-boot:run
```

4. Acesse o banco H2:
   [http://localhost:8080/h2-console](http://localhost:8080/h2-console)
   JDBC URL: `jdbc:h2:mem:testdb`

---

## 🔄 Exemplo de Requisição - Inserir Usuário

```json
POST /users
{
  "name": "Maria Brown",
  "email": "maria@gmail.com",
  "phone": "988888888",
  "password": "123456"
}
```

---

## 📷 Prints ou Demonstração

⚠️ Ainda estou configurando o deploy na AWS. Assim que estiver online, adicionarei prints aqui.

---

## 👨‍💻 Autor

**Mauricio Santiago**
🔗 [LinkedIn](https://www.linkedin.com/in/mauricio-sanntiago)
💻 [GitHub](https://github.com/santiago-26)

---

