# 1. On part de l’image officielle Postgres 17.2 sur Alpine Linux
FROM postgres:17.2-alpine

# 2. On ajoute tous les scripts SQL (initdb/) dans le dossier que Postgres exécute automatiquement au démarrage
COPY initdb/ /docker-entrypoint-initdb.d/

