# 📘 Analyse : Impact des Dépenses Publiques sur la Performance Scolaire aux États-Unis

## 📝 Description

Ce projet explore la relation entre les **dépenses publiques** et la **performance scolaire** aux États-Unis.
À travers une approche de **fouille de données (data mining)** et de **machine learning**, nous analysons comment les différentes catégories de dépenses influencent la réussite scolaire des élèves.

L’analyse est centralisée dans le notebook : **`fouille.ipynb`**.

---

## 🛠️ Technologies utilisées

* **Langage :** Python 3
* **Bibliothèques principales :**

  * Manipulation des données : `pandas`, `numpy`
  * Visualisation : `matplotlib`, `seaborn`
  * Machine Learning : `scikit-learn`
  * Statistiques : `statsmodels`
  * Nettoyage et gestion des valeurs manquantes : `missingno`

---

## 🔍 Contenu du Notebook

Le notebook `fouille.ipynb` contient les étapes suivantes :

1. **Importation des bibliothèques essentielles**
   Préparation de l’environnement pour l’analyse et la modélisation.

2. **Exploration et nettoyage des données**

   * Vérification des valeurs manquantes.
   * Création de variables dérivées (ex. dépenses par élève).
   * Préparation des données pour l’analyse.

3. **Analyse exploratoire (EDA)**

   * Visualisation des distributions des dépenses et revenus scolaires.
   * Étude des corrélations entre dépenses et performance scolaire.
   * Détection de tendances et outliers.

4. **Application du Machine Learning**

   * Construction de modèles de régression.
   * Séparation en **train/test set**.
   * Standardisation des données.

5. **Importance des variables**

   * Identification des catégories de dépenses ayant le plus d’impact sur la performance scolaire.
   * Visualisation et interprétation des résultats.

---

## 📊 Résultats attendus

* Mettre en évidence l’impact relatif des **dépenses publiques** sur la **réussite scolaire**.
* Identifier les postes de dépenses les plus significatifs.
* Fournir des visualisations claires des tendances observées.

---

## ⚡ Utilisation

### Cloner le dépôt

```bash
git clone https://github.com/ton-utilisateur/impact-depenses-scolaires.git
cd impact-depenses-scolaires
```

### Installer les dépendances

```bash
pip install -r requirements.txt
```

### Lancer le notebook

```bash
jupyter notebook fouille.ipynb
```

---

## 📂 Structure du projet

```
impact-depenses-scolaires/
│
├── data/                # Datasets 
├── fouille.ipynb        # Notebook principal d'analyse
├── README.md            # Présentation du projet
```

---

## 🚀 Perspectives

* Étendre l’analyse sur plusieurs années.
* Comparer les résultats entre différents États.
* Intégrer d’autres facteurs socio-économiques (revenu des ménages, taux de pauvreté, etc.).

---