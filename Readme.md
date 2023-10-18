# Quest 1726 - Wild Code School

Ce repository contient une application React ainsi qu'un serveur configurés pour le développement à l'aide de Docker et Docker Compose.

## Prérequis

- Docker doit être installé sur votre machine.

## Instructions de démarrage

1. Clonez ce repository
2. Accédez au répertoire du projet
3. Lancez l'application en mode dev avec Docker Compose :

`docker compose -f docker-compose.dev.yml up --build`

Cette commande construira et lancera les conteneurs Docker nécessaires pour le client React et le serveur. 
Une fois les conteneurs prêts, vous pourrez accéder à l'application React à l'adresse [http://localhost:8080](http://localhost:8080).

## Structure du Projet

- **client/** : Contient le code source de l'application React.
- **server/** : Contient le code source du serveur.