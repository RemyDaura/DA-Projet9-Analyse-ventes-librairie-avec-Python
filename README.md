Analyse des Ventes d'une Librairie en Ligne (Lapage)
Contexte du Projet
Ce projet a été réalisé dans le cadre de mon parcours de Data Analyst. L'objectif était d'exploiter les données de ventes de "Lapage", une grande librairie historique qui vient d'ouvrir sa boutique en ligne, afin d'orienter sa future stratégie marketing.

Mission : Nettoyer les bases de données brutes, réaliser une analyse exploratoire des ventes, et mener une étude statistique rigoureuse pour comprendre le lien entre le profil démographique des clients et leurs habitudes d'achat.

Stack Technique
Langage principal : Python (via Jupyter Notebook).

Manipulation des données : Pandas et NumPy (Data Cleaning, agrégations, jointures).

Data Visualization : Matplotlib et Seaborn.

Mathématiques & Statistiques : SciPy et Statsmodels (Inférence statistique et tests d'hypothèses).

Structure de l'Analyse
Le projet respecte une progression analytique logique, divisée en plusieurs étapes clés :

1_Data_Preparation : La couche de nettoyage.

Standardisation des formats, traitement des valeurs manquantes et des doublons.

Détection et gestion des outliers (données aberrantes).

Exclusion des données de test (utilisateurs factices de la plateforme).

2_EDA_Analyse_Exploratoire : La couche métier et visualisation.

Analyse des indicateurs de performance (CA global, évolution temporelle avec moyenne mobile).

Analyse de l'offre (Tops/Flops des ventes, répartition par catégories).

Création de variables métiers (calcul de l'âge des clients, taille du panier moyen, fréquence d'achat).

3_Tests_Statistiques : La couche d'inférence.

Validation des hypothèses comportementales via des méthodes mathématiques.

Tests Statistiques & Résultats
La robustesse des analyses est garantie par l'utilisation de tests statistiques adaptés à chaque type de variable. Les tests suivants ont été exécutés et interprétés :

Test du Chi-2 : Pour analyser la corrélation entre deux variables qualitatives (ex: Le genre du client et la catégorie de livre achetée).

ANOVA (Analyse de la variance) : Pour évaluer l'impact d'une variable qualitative sur une variable quantitative (ex: L'impact de la catégorie d'âge sur le montant des achats).

Corrélation de Pearson / Spearman : Pour mesurer la relation entre deux variables quantitatives (ex: Le lien entre l'âge et la fréquence d'achat, ou l'âge et le panier moyen).

Ce projet fait partie de la formation Data Analyst d'OpenClassrooms.
