# suivi-candidatures
Application web de suivi de candidatures et de stages, développée en Java 21 avec Spring Boot.

## Problématique

Comment concevoir une application web de suivi de candidatures robuste, sécurisée et maintenable, qui garantit la cohérence du cycle de vie d'une candidature (transitions de statuts valides, historique traçable) et fournit des indicateurs utiles à la prise de décision ?

## Stack

Java 21 · Spring Boot 4 · Spring Data JPA · Spring Security · PostgreSQL · Flyway · Docker · GitHub Actions

## Lancer le projet

```bash
docker compose up -d
./mvnw spring-boot:run
```

L'application est accessible sur http://localhost:8081