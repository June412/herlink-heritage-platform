# HerLink

**CPT202 — Software Engineering Group Project**

A community heritage platform for sharing resources, reviewing submissions, and managing collections. Built with Spring Boot and MySQL.

## Run

Requires Java 17 and MySQL 8. Import [the database schema](backend/sql/init_database.sql) and configure the database connection in [application-local.yml](backend/src/main/resources/application-local.yml).

```bash
cd backend
chmod +x mvnw
./mvnw spring-boot:run
```

Open http://localhost:8080/index.html.
