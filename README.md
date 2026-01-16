# seattle
# 🏙️ Projet Seattle - Analyse de la Consommation Énergétique des Bâtiments

## 📋 Description

Projet d'analyse de données portant sur la consommation énergétique des bâtiments de la ville de Seattle. Ce projet utilise des techniques de machine learning pour prédire et analyser les performances énergétiques des bâtiments en fonction de leurs caractéristiques.

## 🎯 Objectifs

- Analyser les données de consommation énergétique des bâtiments de Seattle
- Identifier les facteurs influençant la consommation d'énergie
- Développer des modèles prédictifs pour estimer la consommation énergétique
- Fournir des insights pour optimiser l'efficacité énergétique

## 🛠️ Technologies Utilisées

- **Python 3.x**
- **Pandas** - Manipulation et analyse de données
- **NumPy** - Calculs numériques
- **Scikit-learn** - Machine learning (régression linéaire, logistique)
- **Matplotlib / Seaborn** - Visualisation de données
- **Jupyter Notebook** - Exploration interactive

## 📊 Dataset

Le projet utilise les données de consommation énergétique des bâtiments de Seattle, incluant :
- Caractéristiques des bâtiments (taille, âge, type)
- Consommation d'énergie (électricité, gaz)
- Émissions de GES
- Scores de performance énergétique

## 🚀 Installation

### Prérequis

```bash
# Créer un environnement conda
conda create -n seattle python=3.13
conda activate seattle
conda install jupyter
```

### Installation des dépendances

```bash
# Installer les packages nécessaires
pip install pandas numpy scikit-learn matplotlib seaborn jupyter --break-system-packages
```

## 📁 Structure du Projet

```
seattle/
│
├── data/                   # Données brutes et traitées
├── notebooks/              # Jupyter notebooks d'exploration
├── scripts/                # Scripts Python
├── models/                 # Modèles entraînés
├── visualizations/         # Graphiques et visualisations
├── .gitignore
└── README.md
```

## 🔍 Utilisation

### Lancer l'analyse exploratoire

```bash
jupyter notebook notebooks/exploration.ipynb
```

### Entraîner les modèles

```bash
python scripts/train_model.py
```

## 📈 Métriques et Résultats

Les modèles sont évalués avec :
- **MSE** (Mean Squared Error)
- **MAE** (Mean Absolute Error)
- **MAPE** (Mean Absolute Percentage Error)
- **R² Score**

## 🧪 Exemples de Code

### Régression Linéaire

```python
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split

# Préparation des données
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Entraînement
model = LinearRegression()
model.fit(X_train, y_train)

# Prédiction
y_pred = model.predict(X_test)
```

## 🎓 Contexte Académique

Ce projet est réalisé dans le cadre de la formation **Data Scientist** proposée par **OpenClassrooms**.

**Compétences développées :**
- Analyse exploratoire de données (EDA)
- Preprocessing et feature engineering
- Modélisation prédictive (régression)
- Évaluation de modèles
- Visualisation de données

## 📝 To-Do

- [ ] Nettoyer et préparer les données
- [ ] Analyse exploratoire complète
- [ ] Feature engineering
- [ ] Tester plusieurs modèles de régression
- [ ] Optimiser les hyperparamètres
- [ ] Créer un rapport final

**Véro** - Étudiante en AI Engineer @ OpenClassrooms
