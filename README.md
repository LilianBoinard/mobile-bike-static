# Mobile Bike - Refonte du site statique

Le projet **Mobile Bike** consiste en la refonte d'un site statique pour un service de location de vélos mobiles. Cette version du site utilise Sass pour la gestion des styles et Browser-sync pour le rechargement automatique en développement.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé [Node.js](https://nodejs.org/) et [npm](https://www.npmjs.com/).

## Installation

1. Clonez le projet sur votre machine locale :

   ```bash
   git clone <url-du-repository>
   ```

2. Installez les dépendances nécessaires :

   ```bash
   npm install
   ```

## Scripts

- **Démarrer le serveur de développement avec Browser-sync et Sass** :

   ```bash
   npm run sass
   ```

  Cette commande surveille les modifications du fichier `styles/main.scss` et compile le CSS dans `dist/styles/main.css`.

## Structure du projet

- `styles/` : Contient les fichiers Sass pour les styles.
- `dist/` : Contient le CSS compilé, ainsi que les fichiers de sortie pour le site.
- `index.html` : La page d'accueil du site.
- `README.md` : Ce fichier, qui décrit le projet.

## Contribuer

1. Fork ce projet.
2. Crée une branche pour ta fonctionnalité (`git checkout -b ma-fonctionnalité`).
3. Commit tes changements (`git commit -am 'Ajout de ma fonctionnalité'`).
4. Pousse ta branche (`git push origin ma-fonctionnalité`).
5. Ouvre une pull request.