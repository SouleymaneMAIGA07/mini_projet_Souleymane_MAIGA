# mini_projet_Souleymane_MAIGA
Analyse et traitement de données GeoNames sur le Burkina Faso :  Extraction, filtrage, et export des résultats en CSV et Excel.

Ce projet illustre les étapes de prétraitement, filtrage et export de données à partir du fichier **BF.txt** (GeoNames - Burkina Faso).

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
