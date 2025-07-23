# 🧪 Prédiction de fertilisants – Kaggle Challenge

Ce projet vise à prédire le nom du fertilisant utilisé à partir de données agronomiques simulées. Il suit une pipeline classique de Machine Learning allant de l'exploration des données jusqu’à la génération automatisée des fichiers de soumission Kaggle.

🔗 [Lien vers la compétition Kaggle](https://www.kaggle.com/competitions/playground-series-s3e16)

## 📂 Contenu du projet

- `01_eda.ipynb` : Analyse exploratoire des données
- `02_modeling.ipynb` : Entraînement et évaluation de plusieurs modèles (Random Forest, LightGBM, etc.)
- `03_submission.ipynb` : Génération des soumissions pour les 4 meilleurs modèles

## ⚙️ Méthodologie

- Nettoyage et visualisation initiale des données
- Encodage, normalisation et sélection de features
- Entraînement multi-modèles avec scoring et tri par accuracy
- Génération des fichiers `.csv` de soumission contenant les **3 classes les plus probables** pour chaque observation

## 🧠 Remarques

Les variables explicatives montrent peu de structure informative :  
> Les distributions sont relativement uniformes et il n'existe pas de corrélation apparente forte avec la variable cible.  
> Une étape de **feature engineering métier** aurait pu significativement améliorer la performance des modèles.
