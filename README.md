# Application Redux avec JavaScript Vanilla

Ce projet est un exemple simple d'utilisation de Redux avec JavaScript vanilla. L'application simule un inventaire de téléphones disponibles à l'achat.

## Structure du projet

Le projet est composé de trois fichiers principaux :

- **index.html** : Contient la structure HTML de l'application.
- **style.css** : Fichier de style pour le design de l'application.
- **script.js** : Code JavaScript implémentant la logique Redux.

## Détails techniques

Fichier script.js

- **Actions** :
- BUY_PHONE : Action pour acheter un téléphone.

- **Reducer** :
- Gestion de l'état initial avec un stock de 5 téléphones.
- Mise à jour de l'état en fonction de l'action BUY_PHONE.

- **Store** :
- Créé avec Redux via Redux.createStore.

**Écoute des évènements**

- Un gestionnaire d'événements est ajouté au bouton "Acheter" pour dispatcher l'action buyPhone.

## Fonctionnalités

- Affichage du nombre de téléphones disponibles.
- Réduction du stock lorsqu'un téléphone est acheté en cliquant sur le bouton "Acheter".

## Prérequis

Aucune installation n'est nécessaire pour exécuter ce projet. Le fichier utilise la bibliothèque Redux directement via un CDN.

## Comment l'utiliser

1. **Téléchargez ou clonez le projet** :
   ```bash
   git clone https://github.com/pricilliaedou/exo1-redux.git
   ```
