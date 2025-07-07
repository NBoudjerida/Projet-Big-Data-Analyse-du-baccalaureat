# 🎓 Analyse des Résultats du Baccalauréat & Prédictions

## 📝 Description du projet

Ce projet a été réalisé dans le cadre d’un cours de Big Data à la Paris School of Business. Il s’appuie sur les données publiques du baccalauréat français (2021–2024) pour analyser les disparités entre académies, filières et profils d’élèves. L’objectif est double : **identifier les inégalités de performance** et **prédire l’obtention d’une mention Très Bien** grâce au machine learning.

L’étude se base sur un jeu de données riche comprenant plus de 34 000 lignes, incluant des variables telles que :
- L’académie
- Le sexe du candidat
- La voie et la série du baccalauréat
- Le statut (scolaire ou apprentissage)
- Le nombre d’inscrits, d’admis, et les mentions obtenues

> 🔍 Peut-on prédire la mention Très Bien à partir de ces variables ?  
> Ce projet propose une réponse à travers une analyse approfondie et un modèle prédictif performant.

---

## 📊 Étapes clés du projet

- **Analyse exploratoire des données (EDA)** : nettoyage, statistiques descriptives, exploration des disparités régionales et structurelles.
- **Préparation des données** : création d’indicateurs (taux de réussite, taux de mention TB), encodage et vectorisation.
- **Visualisations** : compréhension des différences entre académies, voies et genres.
- **Modélisation** : entraînement d’un modèle Random Forest pour prédire l'obtention d'une mention TB.

> 🎯 Résultat : **91,1 % de précision** avec le modèle Random Forest Classifier.

---

## 🧠 Technologies utilisées

- `Python` (Pandas, Scikit-learn, Matplotlib, Seaborn, PySpark)
- `Google Colab` pour l’exécution
- `Random Forest Classifier` pour la prédiction

---
## 📁 Source des données
Les données utilisées proviennent de la plateforme officielle française de données ouvertes :

🔗 Le baccalauréat par académie – Data.gouv.fr

