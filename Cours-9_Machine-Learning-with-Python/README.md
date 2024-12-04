# Prédiction des Précipitations : Projet Final

## Contexte
Dans ce projet final, j'ai utilisé des algorithmes d'apprentissage automatique pour construire un modèle capable de prédire s'il pleuvra le jour suivant, en fonction de données météorologiques historiques. 

L'ensemble de données utilisé provient du **Bureau de météorologie du gouvernement australien**. Ce projet m'a permis de mettre en pratique les compétences acquises durant le cours, notamment le nettoyage de données, la construction de modèles de classification, et l'évaluation des performances à l'aide de différentes métriques.

---

## Objectifs
1. **Nettoyage et préparation des données** :
   - Gérer les valeurs manquantes et les variables non pertinentes.
   - Diviser l'ensemble de données en ensembles d'entraînement et de test.

2. **Construction et évaluation des modèles** :
   - Construire et entraîner les modèles en utilisant les algorithmes suivants :
     - Régression linéaire.
     - KNN (K-Nearest Neighbors).
     - Arbres de décision.
     - Régression logistique.
     - SVM (Support Vector Machines).
   - Évaluer chaque modèle à l'aide des métriques suivantes :
     - Score de précision.
     - Indice de Jaccard.
     - Score F1.
     - Perte logarithmique (si applicable).
     - Erreur absolue moyenne (MAE).
     - Erreur quadratique moyenne (MSE).
     - Score R².

3. **Comparaison des modèles** :
   - Créer un rapport final résumant les performances de chaque algorithme.

---

## Ensemble de Données
- **Source** : Bureau de météorologie du gouvernement australien.
- **Taille de l'ensemble de données** :
  - **Nombre de lignes** : Plus de 3 200 enregistrements.
  - **Colonnes principales** :
    - **Date** : Date de l'observation.
    - **MinTemp** : Température minimale du jour.
    - **MaxTemp** : Température maximale du jour.
    - **Rainfall** : Quantité de précipitations en mm.
    - **Evaporation** : Évaporation en mm.
    - **WindGustDir** : Direction des rafales de vent.
    - **Humidity** : Taux d'humidité.
    - **Pressure** : Pression atmosphérique.
    - **RainTomorrow** : Variable cible binaire (1 = Pluie, 0 = Pas de pluie).
---
