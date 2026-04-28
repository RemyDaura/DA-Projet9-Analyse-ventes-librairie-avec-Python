#  Projet 9 — Analyse des ventes d'une librairie en ligne avec Python
 
> **Formation Data Analyst – OpenClassrooms**
 
---
 
##  Contexte
 
Intervenant en tant que **Data Analyst** pour **Lapage**, une grande librairie historique ayant lancé sa boutique en ligne, j'ai mené une analyse approfondie après deux ans d'activité sur le web.
 
L'objectif : comprendre finement le comportement des clients pour orienter la stratégie marketing de l'entreprise.
 
---
 
##  Objectifs
 
-  Nettoyer et fiabiliser les bases de données issues de la plateforme
-  Réaliser une **analyse exploratoire des ventes** (CA, Tops/Flops)
-  Mener une **étude statistique approfondie** pour identifier les liens entre le profil démographique des clients et leurs habitudes d'achat
---
 
##  Missions réalisées
 
### 1. Préparation & Nettoyage des données *(Data Cleaning)*
- Fusion des tables : **clients**, **produits**, **transactions**
- Traitement des valeurs manquantes
- Gestion des **outliers** (données aberrantes)
- Exclusion des transactions de test (données factices)
### 2. Analyse Exploratoire des Données *(EDA)*
-  Suivi des **KPIs** : évolution du Chiffre d'Affaires et tendance via moyenne mobile
-  Analyse de l'offre : identification des **Tops & Flops**, répartition du CA par catégorie de livres
-  **Profilage client** : création de variables métiers (âge, fréquence d'achat, panier moyen)
### 3. Analyses Statistiques & Bivariées
| Test | Objectif |
|------|----------|
| **Chi-2** | Lien entre le genre du client et les catégories de livres achetées |
| **ANOVA** | Impact de l'âge sur le montant total des achats |
| **Pearson / Spearman** | Relation entre l'âge, la fréquence d'achat et le panier moyen |
 
---
 
##  Stack technique
 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4c8cbf?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
 
| Catégorie | Détail |
|-----------|--------|
| **Langage** | Python |
| **Manipulation de données** | `Pandas` |
| **Visualisation** | `Matplotlib`, `Seaborn` |
| **Statistiques** | `SciPy` |
| **Techniques** | Statistiques descriptives, Tests Chi-2 / ANOVA / Pearson, Analyse bivariée, Data Cleaning |
 
---
 
##  Structure du projet
 
```
 DA-Projet9-Analyse-ventes-librairie-avec-Python/
 ┣ 📓 notebook   # Notebook principal
 ┣ 📂 data-raw/  # Données sources
 ┣ 📂 reports/   # Présentation avec graphiques
 ┗ 📄 README.md
```
 
---
 
*Projet réalisé dans le cadre de la formation [Data Analyst – OpenClassrooms](https://openclassrooms.com/fr/paths/324-data-analyst)*
