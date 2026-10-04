# 📊 Analyse des ventes e-commerce

## 📌 Description

Ce projet consiste à analyser les ventes d'une entreprise e-commerce afin d'identifier les principaux indicateurs de performance et de dégager des tendances à partir des données de ventes.

L'analyse porte notamment sur :

* le chiffre d'affaires ;
* les quantités vendues ;
* les produits ;
* les catégories ;
* les villes ;
* l'évolution des ventes au cours des mois.

## 🎯 Objectifs

* Analyser les données de ventes avec **Python**.
* Calculer le chiffre d'affaires et les quantités vendues.
* Identifier les produits et catégories les plus performants.
* Comparer les performances selon les villes.
* Analyser l'évolution du chiffre d'affaires au cours du temps.
* Créer des visualisations permettant de mieux comprendre les résultats.

## 🛠️ Technologies utilisées

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**
* **Git & GitHub**

## 📂 Structure du projet

```text
projet-data-analysis-ventes/
│
├── data/
│   └── ventes.csv
│
├── images/
│
├── notebooks/
│   └── analyse_ventes.ipynb
│
├── .gitignore
├── README.md
└── requirements.txt
```

## 📊 Principaux résultats

| Indicateur                            |                     Résultat |
| ------------------------------------- | ---------------------------: |
| **Chiffre d'affaires total**          |                **23 980 DT** |
| **Quantité totale vendue**            |                **46 unités** |
| **Produit générant le plus de CA**    |   **Ordinateur — 15 000 DT** |
| **Catégorie générant le plus de CA**  | **Informatique — 21 400 DT** |
| **Produit le plus vendu en quantité** |       **Souris — 18 unités** |
| **Ville générant le plus de CA**      |        **Tunis — 11 790 DT** |
| **Mois générant le plus de CA**       |         **Avril — 7 380 DT** |

## 📈 Visualisations

Le projet contient plusieurs visualisations permettant d'analyser :

* le **chiffre d'affaires par produit** ;
* le **chiffre d'affaires par ville** ;
* l'**évolution du chiffre d'affaires par mois**.

Les visualisations ont été réalisées avec **Matplotlib** et **Seaborn**.

## 💡 Conclusion

L'analyse montre que les **produits informatiques** représentent la principale source de chiffre d'affaires, avec une contribution particulièrement importante des **ordinateurs**.

**Tunis** est la ville la plus performante en termes de chiffre d'affaires et **avril** est le mois le plus performant sur la période étudiée.

La **souris** est cependant le produit le plus vendu en quantité, ce qui montre qu'un produit peut avoir un volume de ventes important sans nécessairement générer le chiffre d'affaires le plus élevé.

## 📁 Données

Le fichier `data/ventes.csv` contient les données utilisées pour l'analyse.

Les principales variables sont :

| Variable    | Description               |
| ----------- | ------------------------- |
| `Date`      | Date de la vente          |
| `Produit`   | Produit vendu             |
| `Categorie` | Catégorie du produit      |
| `Prix`      | Prix unitaire             |
| `Quantite`  | Quantité vendue           |
| `Ville`     | Ville associée à la vente |

## 👩‍💻 Compétences mises en pratique

Ce projet m'a permis de mettre en pratique :

* la manipulation de données avec **Pandas** ;
* les calculs numériques avec **NumPy** ;
* l'exploration et l'analyse des données ;
* les regroupements et agrégations avec `groupby()` ;
* la manipulation des dates avec Pandas ;
* la création de visualisations avec **Matplotlib** et **Seaborn** ;
* l'utilisation de **Jupyter Notebook** ;
* la gestion d'un projet avec **Git et GitHub**.

## 🚀 Installation

### 1. Cloner le projet

```powershell
git clone https://github.com/ZeinebBenJeddou/projet-data-analysis-ventes.git
cd projet-data-analysis-ventes
```

### 2. Créer un environnement virtuel

```powershell
python -m venv .venv
```

### 3. Activer l'environnement virtuel

Sous **Windows PowerShell** :

```powershell
.venv\Scripts\Activate.ps1
```

### 4. Installer les dépendances

```powershell
pip install -r requirements.txt
```

## ▶️ Utilisation

Lancer Jupyter Notebook :

```powershell
python -m notebook
```

Puis ouvrir le notebook :

```text
notebooks/analyse_ventes.ipynb
```

## 🔄 Mise à jour du projet

Après avoir effectué des modifications :

```powershell
git status
git add .
git commit -m "Description des modifications"
git push
```



