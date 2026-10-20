# Crédit Bancaire — Prédiction d'Octroi de Crédit

Projet de classification binaire visant à prédire si une demande de crédit bancaire sera **accordée ou refusée**, à partir du jeu de données public *Loan Prediction* (profil du demandeur : revenus, statut marital, historique de crédit, zone géographique, etc.).

## 📊 Démarche

- Exploration et nettoyage des données (`train_u6lujuX_CVtuZ9i.csv` / `test_Y3wMUE5_7gLdaTN.csv`)
- Encodage des variables catégorielles (`LabelEncoder`)
- Comparaison de plusieurs algorithmes de classification :
  - **Régression Logistique**
  - **K-Nearest Neighbors (KNN)**
  - **Arbre de Décision**
- Sélection du modèle final sur la base de la précision sur l'ensemble de test

## 📈 Résultat

Le modèle retenu est la **régression logistique**, avec une précision d'environ **86 %** sur l'ensemble de test. Le modèle entraîné est sérialisé (`model.pkl`) pour réutilisation.

## 🛠️ Stack technique

Python · Pandas · Scikit-learn · Matplotlib / Seaborn · Jupyter Notebook

## 👤 Auteur

**Japhet Allah-N'diguim**
