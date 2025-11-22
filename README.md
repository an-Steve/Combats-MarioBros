# 🎮 Mini Jeu Mario Bros - Analyse de Données

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red)

## 📋 Description du Projet

Ce projet consiste en une analyse complète d'un dataset de jeu Mario Bros contenant 5000 entrées de parties jouées. L'analyse explore les différentes mécaniques de jeu, les performances des joueurs et les facteurs influençant la victoire.

## 👨‍💻 Auteur

- **ANTON NELCON Steve** - Etudiant en Master 1 Informatique et Big Data

## 🎯 Objectifs du Projet

- Explorer et comprendre la structure des données de jeu Mario Bros
- Analyser les statistiques descriptives des parties
- Identifier les patterns et tendances dans le gameplay
- Préparer les données pour d'éventuelles analyses avancées

## 📊 Structure des Données

Le dataset contient **5000 entrées** avec **8 colonnes** :

| # | Colonne | Type | Description |
|---|----------|------|-------------|
| 1 | player_id | int64 | Identifiant unique du joueur |
| 2 | level | object | Nom du niveau joué |
| 3 | coins | int64 | Nombre de pièces collectées |
| 4 | powerup | object | Type de power-up utilisé |
| 5 | enemy_hit | object | Type d'ennemi rencontré |
| 6 | time_seconds | int64 | Temps de jeu en secondes |
| 7 | death_cause | object | Cause de la mort (si applicable) |
| 8 | win | int64 | Indicateur de victoire (0/1) |

## 🔍 Aperçu des Données

### Statistiques Descriptives

- **Taux de victoire** : 60.36%
- **Pièces moyennes** : 98.56 pièces/partie
- **Temps moyen** : 165.76 secondes
- **Temps min/max** : 30s à 299s

### Valeurs Manquantes

- `powerup` : 1,213 valeurs manquantes (24.26%)
- `death_cause` : 1,030 valeurs manquantes (20.60%)

## 🛠️ Technologies Utilisées

- **Python 3**
- **Pandas** - Manipulation des données
- **Tabulate** - Affichage formaté des tableaux
- **Jupyter Notebook** - Environnement de développement

