# 🏢 Prédiction du Turnover - TechNova

> Projet 10 - OpenClassrooms : "Classifiez automatiquement des informations grâce au Machine Learning"

**Étudiant :** William Derue

---

## 📋 Description

Ce projet simule une mission pour **TechNova**, une ESN (Entreprise de Services Numériques) confrontée à un turnover important. L'objectif est de construire un modèle de Machine Learning capable de prédire quels employés risquent de quitter l'entreprise, afin d'identifier les causes racines des départs.

---

## 📁 Structure du projet

```
├── source/
│   ├── extrait_sirh.csv       # Données RH (âge, salaire, poste...)
│   ├── extrait_eval.csv       # Évaluations des employés
│   └── extrait_sondage.csv    # Résultats de sondages internes
├── Derue_William_1_notebook_012026.ipynb  # Notebook principal
├── pyproject.toml             # Dépendances Python
└── README.md
```

---

## 🚀 Installation

```bash
# Cloner le projet
git clone <url-du-repo>
cd OC-P10-TechNova-main

# Installer les dépendances (avec uv)
uv sync
```

---

## 🛠️ Technologies utilisées

- **Python 3.11+**
- **Pandas** - Manipulation des données
- **Scikit-learn** - Modélisation ML
- **XGBoost** - Modèle de boosting
- **SHAP** - Interprétabilité des modèles
- **Imbalanced-learn** - Gestion du déséquilibre de classes

---

## 📊 Méthodologie

1. **Chargement & Fusion** des 3 sources de données
2. **Analyse Exploratoire (EDA)** - Identification des variables discriminantes
3. **Preprocessing & Feature Engineering**
4. **Modélisation** avec gestion du déséquilibre (SMOTE)
5. **Interprétabilité** via SHAP

---

## 📝 Licence

Projet réalisé dans le cadre de la formation Dev IA - OpenClassrooms (2026)