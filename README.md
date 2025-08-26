# ⚡ Ordem em Código

API REST desenvolvida em **Java com Spring Boot e JPA**.  
Gerencia entidades como **usuários, pedidos, produtos e categorias**, permitindo operações completas de CRUD.

---

## 🚀 Tecnologias
- Java 17+
- Spring Boot 2.x
- Spring Data JPA / Hibernate
- H2 Database (para testes)
- Maven

---

## ▶️ Como executar

### Rodar com Maven
```bash
mvn spring-boot:run
```

## 💻 Gerar JAR e executar
```bash
mvn -DskipTests package
java -jar target/*.jar
```
## 📂 Estrutura resumida
src/
 ├── main/
 │   ├── java/com/educandoweb/course/...
 │   └── resources/
 │        ├── application.properties
 │        ├── banner.txt
 └── test/...

## 📌 Endpoints principais
/users – gerenciamento de usuários
/products – gerenciamento de produtos
/orders – gerenciamento de pedidos
/categories – gerenciamento de categorias