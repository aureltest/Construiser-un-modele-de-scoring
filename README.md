# 📊 Construisez un Modèle de Scoring

> **Projet 4** — Parcours Ingénieur IA · OpenClassrooms

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006600?style=flat-square&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## 🎯 Contexte du projet

Au sein d'une **société financière**, l'objectif est de construire un **modèle de scoring** capable de prédire la probabilité de défaut de paiement d'un client. Ce modèle aide les équipes métiers à prendre des décisions éclairées concernant l'octroi de crédits.

## 🧠 Compétences développées

- **Feature Engineering** — Transformation et sélection des variables pertinentes pour optimiser les performances du modèle
- **Apprentissage supervisé** — Entraînement et comparaison de modèles classiques (Régression Logistique, Random Forest, XGBoost, LightGBM)
- **Optimisation d'hyperparamètres** — Grid Search, Random Search et validation croisée pour affiner les modèles
- **Évaluation de performance** — Analyse des métriques adaptées au contexte métier (AUC-ROC, F-beta Score, matrice de confusion)

## 🔬 Approche méthodologique

```
1. Analyse exploratoire des données (EDA)
2. Nettoyage et prétraitement (valeurs manquantes, outliers, encodage)
3. Feature engineering et sélection de variables
4. Entraînement de modèles supervisés
5. Optimisation des hyperparamètres
6. Évaluation et sélection du meilleur modèle
7. Analyse de l'importance des features
```

## 🛠️ Stack technique

| Catégorie | Technologies |
|-----------|-------------|
| **Langage** | Python 3.8+ |
| **Data Manipulation** | Pandas, NumPy |
| **Machine Learning** | scikit-learn, XGBoost, LightGBM |
| **Visualisation** | Matplotlib, Seaborn |
| **Environnement** | Jupyter Notebook |

## 📁 Structure du projet

```
├── notebooks/
│   ├── 01_exploration.ipynb        # Analyse exploratoire des données
│   ├── 02_preprocessing.ipynb      # Nettoyage et feature engineering
│   └── 03_modelisation.ipynb       # Entraînement et évaluation des modèles
├── data/                           # Données (non incluses)
└── README.md
```

## 📌 Points clés

- Prise en compte du **déséquilibre des classes** (techniques de resampling, SMOTE)
- Optimisation du **seuil de décision** pour minimiser le coût métier (faux négatifs vs faux positifs)
- Interprétabilité du modèle via l'**importance des features** et les valeurs SHAP

---

## 👤 Auteur

**Aurélien T.** — Data Scientist & Ingénieur IA  

---

*Projet réalisé dans le cadre du parcours [Ingénieur IA](https://openclassrooms.com/fr/paths/188-ingenieur-ia) d'OpenClassrooms*
