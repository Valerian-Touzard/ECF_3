# Projet LOCALIB

## Présentation

Ce projet est un projet de fin de formation de CDA. Il a pour but de mettre en pratique les compétences acquise
en créant une application de gestion de location.

## Prérequis

* Java 11+
* [docker](https://www.docker.com/products/docker-desktop)
* [Maven](https://maven.apache.org/download.cgi)
* [docker-compose](https://docs.docker.com/compose/install/)
* Un IDE Java ([Eclipse](https://www.eclipse.org/downloads/), [IntelliJ](https://www.jetbrains.com/fr-fr/idea/))
* [Postman](http://www.postman.com)

## Installation

### Installation des prérequis



rendez-vous dans le dossie ECF_Backend puis
dans un terminal, exécutez les commandes suivantes:
```bash
mvn clean package
```
puis revener a la racine et exécutez la commande suivante: 

```bash
docker compose up -d
```

## Utilisation

### Utilisation de l'application

L'application est accessible à l'adresse suivante: [http://localhost:3000](http://localhost:3000)