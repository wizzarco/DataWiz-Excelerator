# DataWiz Excelerator

[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://wizzarco.com/)

## Description

**DataWiz Excelerator** est une application web conçue pour transformer et optimiser les données en fichiers Excel structurés pour une analyse ultérieure dans des outils comme Tableau. Cet outil s'adresse particulièrement aux analystes de données et aux professionnels travaillant régulièrement avec des données SQL ou CSV, en leur offrant une plateforme conviviale pour convertir ces données en un format exploitable.

## Fonctionnalités

- **Importation de Fichiers** : Prend en charge l'importation de fichiers SQL et CSV.
- **Conversion de Données** : Convertit les données en feuilles Excel distinctes selon les critères définis par l'utilisateur.
- **Optimisation pour Tableau** : Les fichiers Excel générés sont préparés pour une utilisation immédiate dans Tableau.
- **Interface Utilisateur Intuitive** : Une interface simple et conviviale pour une interaction facile.

## Technologies Utilisées

- **Front-End** : Vue.js 3, Vue Router, Tailwind CSS
- **Back-End** : (Si applicable, détaillez les technologies back-end utilisées)
- **Dépendances Notables** : Node.js, npm

## Installation

Assurez-vous d'avoir Node.js et npm installés sur votre machine. Pour vérifier, exécutez `node -v` et `npm -v` dans votre terminal.

### Étapes d'installation :

1. **Cloner le dépôt** :
    Ouvrez un terminal et exécutez la commande suivante pour cloner le dépôt :
    Git clone [URL du dépôt GitHub]
    cd datawiz-excelerator-front

2. **Installer les dépendances** :
Dans le dossier du projet, exécutez la commande suivante pour installer les dépendances nécessaires :
    npm install


3. **Lancer l'application** :
Lancez l'application en exécutant la commande suivante :
    npm run serve


Après le lancement de l'application, ouvrez votre navigateur et accédez à `http://localhost:8080` (ou le port indiqué dans votre terminal).

### Importation de Fichier :

1. Cliquez sur le bouton d'importation et sélectionnez le fichier SQL ou CSV que vous souhaitez convertir.
2. Configurez les options de conversion selon vos besoins.
3. Cliquez sur 'Convertir' pour démarrer le processus de conversion.

### Téléchargement des Fichiers Excel

Une fois la conversion terminée, un lien de téléchargement pour le fichier Excel généré sera disponible.