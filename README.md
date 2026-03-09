# HelloJo – Carte de distance depuis Nantes

Petit outil web de cartographie qui affiche une carte centrée sur Nantes et permet de :
- régler un rayon autour de Nantes ;
- chercher une adresse ou cliquer sur la carte ;
- calculer l’itinéraire routier, la distance et le temps de trajet.

## Démo rapide

1. Ouvrir `index.html` dans un navigateur moderne (Chrome, Firefox, Edge…).
2. Déplacer le curseur pour changer le rayon autour de Nantes.
3. Saisir une adresse ou cliquer sur la carte pour poser un point.
4. Lire la distance et le temps de trajet dans le panneau de résultats.

## Fonctionnalités

- Carte interactive basée sur OpenStreetMap.
- Rayon ajustable autour de Nantes (en km).
- Recherche d’adresse (géocodage) et clic sur la carte.
- Calcul d’itinéraire routier (distance + durée).
- Interface responsive (PC et mobile).

## Fonctionnalités à venir

- Choisir librement sa ville de départ (pas seulement Nantes).

## Prérequis

- Navigateur récent avec connexion Internet, pour :
  - le chargement des tuiles de carte,
  - la recherche d’adresses,
  - le calcul des itinéraires routiers.

## Bibliothèques et services utilisés

- Leaflet pour l’affichage de la carte.
- Leaflet Routing Machine pour le calcul de routes.
- OpenStreetMap / Nominatim pour la recherche d’adresses.
- Service OSRM public pour les itinéraires.

Chaque service possède sa propre licence et politique d’usage (quotas, fair‑use, etc.). Vérifiez les conditions avant un usage intensif ou en production.

## Installation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/ton-compte/hellojo.git



## Démo

1. Ouvrir la page :
   ```bash
   https://hellojo44.github.io/Carte_Nantes_distance-kilometre/ 
