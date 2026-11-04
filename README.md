# TRUCK GPS

Prototype Android-friendly de planification de tournée pour porteur en France.

## Profil véhicule de départ
- Porteur avec hayon
- Hauteur : 3,40 m
- Largeur : 2,55 m
- Longueur : 8,00 m
- PTAC : 11 800 kg

## Fonctions du prototype
- Carte OpenStreetMap
- Recherche d'adresses en France
- Départ et destinations multiples
- Réorganisation et suppression des étapes
- Calcul d'itinéraire HERE Routing API v8 en mode camion, après ajout d'une clé API
- Paramètres véhicule transmis au moteur : hauteur 340 cm, largeur 255 cm, longueur 800 cm, masse brute 11800 kg

## Lancer
Le site peut être servi depuis GitHub Pages. Dans GitHub : Settings > Pages > Deploy from a branch > main > / (root).

## Clé HERE
Créer un projet et une clé dans le portail développeur HERE. La clé saisie dans l'interface est conservée dans le stockage local du navigateur. Pour une application publique ou une vraie mise en production, ne pas exposer une clé privilégiée côté client : utiliser une restriction de domaine et/ou un serveur intermédiaire avec secrets côté serveur.

## Limites de sécurité
Ceci est un prototype de développement, pas un système de navigation certifié. Les données de restrictions poids lourds peuvent être incomplètes ou évoluer. Ne pas l'utiliser comme seule source pour décider qu'une route est praticable. Toujours respecter panneaux, arrêtés et consignes locales. Le guidage vocal, navigation en arrière-plan, alertes fiables, optimisation automatique des tournées et tests terrain restent à développer.

Les cartes et services de recherche/routage nécessitent une connexion Internet.
