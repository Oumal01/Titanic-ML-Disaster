# Titanic-ML-Disaster
Ce projet est une participation à la célèbre compétition [Kaggle Titanic](https://www.kaggle.com/competitions/titanic), visant à prédire la survie des passagers à partir de données réelles issues du naufrage du Titanic.
L'objectif est de construire un modèle de classification binaire capable de prédire si un passager a survécu ou non, en se basant sur ses caractéristiques (âge, sexe, classe, etc.).

### 1. Prétraitement des données

- Traitement des valeurs manquantes (Imputation)
- Encodage des variables catégorielles (`Sex`, `Embarked`)
- Feature engineering : création de nouvelles variables (`FamilySize`, `IsAlone`, `Title`)
- Normalisation des données 

### 2. Exploration des données (EDA)

- Analyse statistique des variables
- Visualisations ( taux de survie selon le sexe,  etc.)
- Corrélation entre les variables

### 3. Modélisation

Les modèles testés :

- **Arbre de décision**
- **Random Forest Classifier**
- **optimiser les hyperparmetres grâce à grid**

Évaluation via :

- Matrice de confusion
- Précision (`accuracy`)


## 4. Résultats

| Modèle              | Accuracy | 
|---------------------|----------|
| Decision Tree       | 78%      |           
| Random Forest       | 78%    |            

---
