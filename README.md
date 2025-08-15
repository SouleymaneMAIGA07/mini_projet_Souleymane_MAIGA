# mini_projet_Souleymane_MAIGA
Analyse et traitement de données GeoNames sur le Burkina Faso :  Extraction, filtrage, et export des résultats en CSV et Excel.

## Description
Ce projet consiste à analyser et traiter les données GeoNames pour le Burkina Faso.  
Les principales étapes incluent l'extraction, le filtrage et l'export des résultats sous formats CSV et Excel.  
Le projet est réalisé en Python avec la bibliothèque `pandas`.

## Étapes principales
1. Lecture du fichier `BF.txt`.
2. Filtrage des colonnes utiles (`ID`, `location_name`, `lat`, `long`).
3. Extraction :
   - Noms contenant "gounghin"
   - Noms commençant par A → P
4. Recherche des coordonnées minimales.
5. Export en CSV et Excel multi-feuilles.

## Exécution
Installez les dépendances :
```bash
pip install -r requirements.txt
