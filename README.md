# HerLink

**CPT202 — Software Engineering Group Project**

A community heritage platform for browsing and sharing resources, reviewing submissions, and managing collections. Built with Spring Boot and MySQL, it supports contributors, reviewers, and administrators, with comments and feedback for visitors.

[Original project](https://github.com/suibianlong/CPT202-Final)

## Run

Requires Java 17 and MySQL 8. Import [the database schema](backend/sql/init_database.sql) and configure the database connection in [application-local.yml](backend/src/main/resources/application-local.yml).

```bash
cd backend
chmod +x mvnw
./mvnw spring-boot:run
```

