# Sell4All - Exploration et Nettoyage des Données

## Présentation du projet

Sell4All est une entreprise qui vend des vêtements d'occasion en ligne. Elle souhaite utiliser l'intelligence artificielle pour proposer des recommandations de produits à ses clients.

Avant de créer ce système de recommandation, il est nécessaire d'explorer les données disponibles et de les nettoyer afin de préparer un jeu de données fiable.

L'objectif de ce projet est donc d'analyser les données des clients, d'effectuer quelques calculs statistiques, de créer une visualisation et de nettoyer les données avant de les exporter dans un nouveau fichier CSV.

---

## Fonctionnalités réalisées

Le notebook permet de :

- Lire le fichier `dataset-sell4all.csv`
- Afficher les 5 premières lignes du jeu de données
- Afficher le résumé technique avec `df.info()`
- Expliquer les informations affichées par le résumé technique
- Calculer la moyenne et la médiane des colonnes **Age** et **Customer spendings**
- Calculer l'âge médian par pays (bonus)
- Créer un graphique à barres représentant les dépenses des clients par pays
- Supprimer les clients ayant dépensé moins de **10 €**
- Supprimer les lignes dupliquées
- Exporter un nouveau fichier `dataset-sell4all-cleaned.csv` contenant uniquement les colonnes demandées :
  - Country
  - Age
  - Gender
  - Customer spendings

---

## Étapes de réalisation

### Jour 1

- Installation de Python, Jupyter Notebook et des bibliothèques nécessaires
- Lecture du fichier CSV
- Affichage des 5 premières lignes
- Analyse du résumé technique
- Rédaction des explications demandées

### Jour 2

- Calcul de la moyenne et de la médiane
- Calcul de l'âge médian par pays
- Création du graphique à barres
- Amélioration de la présentation du graphique
- Nettoyage des données

### Jour 3

- Suppression des doublons
- Export du nouveau fichier CSV
- Vérification du notebook
- Rédaction du README et organisation du dépôt GitHub

---

## Difficultés rencontrées

Pendant la réalisation du projet, quelques difficultés ont été rencontrées.

- Les noms des pays se chevauchaient sur le graphique.
  - **Solution :** rotation des noms avec `plt.xticks(rotation=90)`.

- Les valeurs affichées au-dessus des barres étaient coupées.
  - **Solution :** ajout d'une marge avec `plt.margins(y=0.2)`.

---

## Exécution du projet

### Prérequis

- Python 3.11.7
- Jupyter Notebook
- Pandas
- Matplotlib

### Installation des bibliothèques

```bash
pip install pandas matplotlib notebook
```

### Lancer le projet

```bash
jupyter notebook
```

Ouvrir ensuite le fichier **exploration.ipynb** et exécuter toutes les cellules.

---

## Structure du projet

```
youcode-project/
│
├── dataset-sell4all.csv
├── dataset-sell4all-cleaned.csv
├── exploration.ipynb
└── README.md
```

---

## Auteur

**Anas El Khadiri**

- GitHub : [Anas-EL-KHADIRI](https://github.com/Anas-EL-KHADIRI)
- LinkedIn : [Anas El Khadiri](https://linkedin.com/in/anas-el-khadiri)
- Portfolio : [Portfolio](https://rugale-portfolio.netlify.app)