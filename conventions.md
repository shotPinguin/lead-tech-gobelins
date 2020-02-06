# Pratiques existantes en entreprise

## Développement

### Back office
Utilisation du framework MVC PHP Symfony. 
Chaque nouveau projet est créé à partir de la dernière version stable du framework. Actuellement 5.0.3.

### Front office
Utilisation de Webpack avec Symfony pour compiler les assets.

## Base de données

Utilisation d'une base de données MongoDB lié à Symfony par l'ORM Doctrine.

## Git
Chaque projet est gitté avec une convention de nommage précise : N°PROJET-NOMCLIENT-NOMPROJET_ANNEE.
Les commits sont effectués à chaque nouvelle fonctionnalité ajoutée selon le nommage : TYPEMODIFICATION [FONCTIONNALITE] DESCRIPTION COMMIT.
Exemple : UPD [config] modification config pour mise en prod.

## Serveur
Utilisation d'un serveur de preprod pour tester tous les projets avant une mise en production.
