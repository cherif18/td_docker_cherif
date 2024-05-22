# td_docker_cherif
Td module docker
## Composants

- MariaDB : Base de données relationnelle.
- phpMyAdmin: Outil de gestion de base de données via une interface web.
- BFF : Backend-for-Frontend qui fournit une API pour le frontend.

## Configuration

Le projet utilise `docker-compose` pour orchestrer les différents services. Vous devez avoir Docker et Docker Compose installés sur votre machine pour exécuter ce projet.

## Structure du projet

- `bff/target` : Contient le Dockerfile et le code source du BFF.
- `front/browser` : Contient le code source du frontend (non détaillé ici).
- `docker-compose.yml` : Fichier de configuration qui définit les services, réseaux et volumes.

## Démarrage rapide

Pour démarrer tous les services, exécutez la commande suivante dans le répertoire racine du projet :

```bash
docker-compose up
```

Lien dockerHub :

- front: https://hub.docker.com/r/sirifou/frontend
- back : https://hub.docker.com/r/sirifou/backend
