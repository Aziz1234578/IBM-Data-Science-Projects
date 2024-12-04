# Analyse de l'Impact des Récessions sur les Ventes Automobiles

## Contexte
Dans ce projet final, j'ai pris le rôle d'un data scientist pour **XYZAutomotives**, une entreprise spécialisée dans la vente automobile. Mon objectif était d'analyser les données historiques afin de fournir des insights aux directeurs de l'entreprise concernant l'impact des récessions économiques sur les ventes de véhicules.

À l'aide des bibliothèques Python comme **Matplotlib**, **Seaborn**, **Folium**, et **Dash**, j'ai créé des visualisations et des tableaux de bord interactifs pour explorer les tendances des ventes, les facteurs économiques et les publicités pendant les périodes de récession.

---

## Objectifs
### Partie 1 : Création de Visualisations
1. Explorer les tendances des ventes automobiles pendant les périodes de récession et de non-récession.
2. Comparer les performances des différents types de véhicules.
3. Analyser l'impact des facteurs économiques, tels que le **PIB**, le **taux de chômage**, et la **confiance des consommateurs**, sur les ventes.
4. Identifier les corrélations entre les prix des véhicules, les dépenses publicitaires, et les volumes de ventes.

### Partie 2 : Création de Tableaux de Bord Interactifs
1. Développer une application **Dash** pour permettre aux directeurs d'interagir avec les données.
2. Ajouter des fonctionnalités de filtrage (années, types de véhicules, périodes de récession) pour affiner l'analyse.

---

## Ensemble de Données
- **Source** : Données artificielles créées spécifiquement pour ce projet.
- **Périodes de récession étudiées** :
  - 1980
  - 1981–1982
  - 1991
  - 2000–2001
  - Fin 2007–mi-2009
  - 2020 (COVID-19, Février–Avril)
- **Taille de l'ensemble de données** :
  - **Nombre de lignes** : Plus de 500 enregistrements.
  - **Nombre de colonnes** : 15 caractéristiques, incluant :
    - **Date** : Date de l'observation.
    - **Recession** : Indicateur binaire (1 = récession, 0 = non-récession).
    - **Automobile_Sales** : Nombre de véhicules vendus.
    - **GDP** : PIB par habitant en USD.
    - **Unemployment_Rate** : Taux de chômage mensuel.
    - **Consumer_Confidence** : Indice de confiance des consommateurs.
    - **Seasonality_Weight** : Impact de la saisonnalité sur les ventes.
    - **Price** : Prix moyen des véhicules.
    - **Advertising_Expenditure** : Dépenses publicitaires.
    - **Vehicle_Type** : Catégorie du véhicule (e.g., Small family car, Sports).
    - **Competition** : Indicateur de concurrence sur le marché.

---
