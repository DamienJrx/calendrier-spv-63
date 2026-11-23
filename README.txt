# Calendrier SPV 63 — version 1

Application web personnelle pour suivre une tournée de calendriers.

## Fonctionnalités
- Maisons/adresses et statuts : à faire, visité, absent, à repasser
- Dons en espèces ou chèques
- Tableau de bord et statistiques
- Carte Leaflet/OpenStreetMap avec coordonnées GPS
- Géolocalisation et lien d'itinéraire Apple Plans
- Export/import JSON pour transférer les données entre appareils
- Interface responsive iPhone/Mac et base PWA

## Important
Les données sont stockées localement dans le navigateur (localStorage). Elles ne sont pas synchronisées automatiquement entre iPhone et Mac. Exporter régulièrement une sauvegarde JSON et l'importer sur l'autre appareil.
La carte et les bibliothèques externes nécessitent une connexion Internet. La carte ne fonctionne pas hors ligne. N'inscrivez pas de données personnelles sensibles concernant les habitants.

## Publication gratuite avec GitHub Pages
1. Créer un compte GitHub.
2. Créer un nouveau dépôt (repository) nommé `calendrier-spv-63`.
3. Pour un dépôt public, les fichiers du code seront visibles publiquement, mais les données enregistrées dans le navigateur ne sont pas publiées.
4. Téléverser `index.html`, `manifest.json` et `sw.js` à la racine du dépôt.
5. Dans Settings > Pages, choisir Deploy from a branch, `main`, `/ (root)`, puis Save.
6. Attendre la publication. L'adresse sera de la forme `https://VOTRE-PSEUDO.github.io/calendrier-spv-63/`.
7. Ouvrir cette adresse dans Safari sur iPhone, toucher Partager, puis « Sur l'écran d'accueil ».

## Sauvegarder/transférer
Dans l'application > Sauvegarde > Exporter mes données. Sur l'autre appareil, ouvrir l'application > Sauvegarde > Importer JSON.
