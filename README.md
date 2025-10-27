# Tricol - Module Fournisseurs

## Description
Module de gestion des fournisseurs pour l'application Tricol. Ce module permet de gérer les informations des fournisseurs de l'entreprise.

## Technologies
- **Java**: 11
- **Spring Framework**: 5.3.31
- **Spring Data JPA**: 2.7.18
- **Hibernate**: 5.6.15.Final
- **MySQL**: 8.0.33
- **Tomcat**: 9.0.x compatible
- **Maven**: Gestion des dépendances

## Architecture
Le projet suit une architecture en couches:
- **Model**: Entités JPA (`Fournisseur`)
- **Repository**: Spring Data JPA repositories
- **Service**: Logique métier
- **Controller**: REST API endpoints
- **Config**: Configuration Java (JPA, Spring MVC)



## Endpoints API

### Fournisseurs
- `GET /api/fournisseurs` - Liste tous les fournisseurs
- `GET /api/fournisseurs/{id}` - Récupère un fournisseur par ID
- `POST /api/fournisseurs` - Crée un nouveau fournisseur
- `PUT /api/fournisseurs/{id}` - Met à jour un fournisseur
- `DELETE /api/fournisseurs/{id}` - Supprime un fournisseur


