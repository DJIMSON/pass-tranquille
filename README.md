# Pass'Tranquille 🚌
Optimiseur de trajets multimodaux — JOJ Dakar 2026

## Base de données
- PostgreSQL 16 + PostGIS 3
- Tables : noeuds, aretes, sites_joj

## Pour utiliser la base
1. Créer la base : CREATE DATABASE pass_tranquille;
2. Activer PostGIS : CREATE EXTENSION postgis;
3. Exécuter le fichier : schema_pass_tranquille.sql
