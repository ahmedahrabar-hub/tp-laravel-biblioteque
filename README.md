# TP Bibliothèque — API REST Laravel

API REST de gestion des emprunts de livres d'une bibliothèque.

## Technologies utilisées
- Laravel 12
- PHP 8.4
- MySQL 8
- Docker

## Endpoints

| Méthode | URL | Description |
|---------|-----|-------------|
| GET | /api/loans | Lister tous les emprunts |
| POST | /api/loans | Créer un emprunt |
| GET | /api/loans/{id} | Afficher un emprunt |
| PUT | /api/loans/{id} | Modifier un emprunt |
| PATCH | /api/loans/{id}/return | Marquer comme rendu |
| DELETE | /api/loans/{id} | Supprimer un emprunt |

## Lancer le projet
```bash
docker-compose up --build
```

## Auteur
Ton Nom — Département Génie Informatique et IA
