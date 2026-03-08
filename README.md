# Projet Dashboard Interactif d’Analyse des Taux de Suicide aux États-Unis (2000-2018)

## Auteur

**Amine Nakrou**

---

## Accès au site

Le dashboard est accessible en ligne à l’adresse suivante :

🔗 [[**https://aminenakrou.github.io/Projet_Dashboard_Interactif/**](https://aminenakrou.github.io/Projet_Dashboard_Interactif/)](https://aminenakrou.github.io/Projet_Dashboard_Interactif/)

---

## Présentation du projet

Ce projet est un **dashboard interactif de data visualisation** consacré à l’analyse des taux de suicide aux **États-Unis** entre **2000 et 2018**.

Son objectif est de proposer une interface web claire, moderne et interactive permettant d’explorer les données, de mettre en évidence des tendances et de faciliter l’interprétation d’indicateurs statistiques à travers différentes visualisations.

Le site a été conçu comme une application web statique, accessible directement depuis un navigateur, sans backend, et déployée en ligne via **GitHub Pages**.

---

## Objectifs du projet

Ce projet a été réalisé pour :

- visualiser l’évolution des taux de suicide aux États-Unis sur une période de 18 ans ;
- présenter les données sous une forme plus lisible et plus pédagogique ;
- proposer une navigation simple entre plusieurs pages d’analyse ;
- combiner plusieurs techniques de visualisation dans un même dashboard ;
- mettre en pratique des compétences en développement web front-end et en data visualisation.

---

## Description fonctionnelle

Le dashboard s’organise autour de plusieurs pages principales :

- `accueil.html` : page d’introduction et de navigation principale ;
- `analyse.html` : page dédiée à l’exploration et à l’interprétation des données ;
- `indicateurs.html` : page orientée synthèse, mettant en avant des indicateurs visuels et statistiques.

### Dashboard interactif

Le projet repose sur la logique d’un **dashboard interactif**, c’est-à-dire une interface visuelle qui permet à l’utilisateur d’explorer rapidement un ensemble de données à travers plusieurs composants graphiques, plusieurs vues et plusieurs niveaux de lecture.

L’interactivité permet d’améliorer l’expérience utilisateur en rendant les résultats plus accessibles, plus dynamiques et plus faciles à interpréter qu’un simple tableau brut.

### Partie analyse

La partie **analyse** vise à approfondir la lecture des données.

Elle permet de mettre en évidence :
- les évolutions dans le temps ;
- les tendances globales ;
- les écarts observés selon les représentations choisies ;
- les relations possibles entre plusieurs variables visibles dans les graphiques.

L’objectif de cette page est donc de passer d’une simple consultation à une **lecture analytique** des données.

### Partie indicateurs

La partie **indicateurs** sert à synthétiser l’information à travers des éléments plus rapides à lire.

On y retrouve l’idée d’un tableau de bord décisionnel :
- affichage de valeurs clés ;
- mise en avant d’indicateurs importants ;
- lecture visuelle rapide ;
- support de comparaison et de suivi.

Cette partie est utile pour obtenir une vue d’ensemble sans devoir parcourir toute l’analyse détaillée.

---

## Technologies utilisées

Le projet repose principalement sur les technologies suivantes :

### Langages

- **HTML** pour structurer les pages du site ;
- **CSS** pour la mise en forme ;
- **JavaScript** pour l’interactivité et la logique côté client.

### Framework et bibliothèques

- **Bootstrap** pour construire une interface responsive, structurée et plus rapide à mettre en place ;
- **Plotly.js** pour générer des graphiques interactifs de data visualisation ;
- **Leaflet** pour intégrer des fonctionnalités de cartographie interactive ;
- **Cytoscape.js** pour la visualisation de graphes ;
- **Dagre** pour l’agencement de graphes ;
- **jQuery** pour certaines manipulations et interactions côté front-end.

---

## Rôle des outils utilisés

### Bootstrap

Bootstrap est utilisé pour améliorer la présentation générale du dashboard.

Il permet notamment :
- d’obtenir une interface plus propre et cohérente ;
- de construire une mise en page responsive ;
- d’adapter l’affichage à différentes tailles d’écran ;
- d’utiliser des composants visuels prêts à l’emploi.

Cela permet d’avoir un site plus agréable à utiliser sur ordinateur comme sur d’autres supports.

### Plotly

Plotly est utilisé pour la **data visualisation interactive**.

Cette bibliothèque permet de créer des graphiques dynamiques, lisibles et riches, ce qui est particulièrement utile dans un projet centré sur l’analyse statistique et visuelle de données.

Elle facilite l’exploration des informations et rend les graphiques plus parlants pour l’utilisateur.

### Leaflet

Leaflet est intégré pour les fonctionnalités de **cartographie interactive**.

Même lorsqu’une carte n’est pas l’élément principal du projet, cette bibliothèque permet d’ajouter une dimension géographique ou spatiale à l’analyse, avec une interface légère et adaptée au web.

### Cytoscape.js et Dagre

Ces bibliothèques permettent de gérer et représenter des graphes ou des structures visuelles plus complexes.

Elles peuvent enrichir le dashboard lorsque l’on souhaite afficher des relations, des connexions ou des organisations visuelles entre éléments.

---

## Données exploitées

Le projet utilise un fichier de données principal :

- `data/suicide.csv`

Ce fichier sert de base au chargement, au traitement et à l’affichage des visualisations du dashboard.

L’ensemble des pages et des scripts JavaScript s’appuie sur ces données pour produire des graphiques, des analyses et des indicateurs.

---

## Structure du projet

```bash
.
│   accueil.html
│   analyse.html
│   indicateurs.html
│
├── css
│   ├── bootstrap.min.css
│   └── bootstrap.min.css.map
│
├── data
│   └── suicide.csv
│
├── img
│   ├── capture1.png
│   ├── capture2.png
│   ├── capture3.png
│   ├── capture4.png
│   ├── capture5.png
│   └── logo_ecole.png
│
├── js
│   ├── bootstrap.min.js
│   ├── bootstrap.min.js.map
│   ├── cytoscape-dagre.js
│   ├── cytoscape.min.js
│   ├── dagre.min.js
│   ├── jquery-3.2.1.slim.min.js
│   ├── js-fluid-meter.js
│   ├── plotly-2.18.0.min.js
│   ├── popper.min.js
│   ├── readfile.js
│   └── suicide.js
│
└── Leaflet
    ├── leaflet-src.esm.js
    ├── leaflet-src.esm.js.map
    ├── leaflet-src.js
    ├── leaflet-src.js.map
    ├── leaflet.css
    ├── leaflet.js
    └── leaflet.js.map
