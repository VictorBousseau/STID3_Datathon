# Datathon SNCF Gare & Connexion

Développement d'une solution pour prédire les affluences atypiques liées aux événements sociaux.

Ce projet a été réalisé dans le cadre d'un Datathon pour SNCF Gares & Connexions, visant à analyser les données de fréquentation des gares et à développer des modèles prédictifs et descriptifs.

## Objectifs du projet

L'objectif principal est de comprendre et de prédire les variations de fréquentation dans les gares, en particulier lors d'événements atypiques ou sociaux. Le projet se décline en plusieurs volets :

1.  **Analyse Descriptive et Exploratoire** : Visualisation des données de fréquentation journalière, analyse des distributions par gare (Box Plots), et étude des tendances temporelles (par année, mois, jour, semaine).
2.  **Analyse Multivariée (ACM)** : Utilisation de l'Analyse des Correspondances Multiples pour explorer les relations entre les différentes variables catérogiques.
3.  **Modélisation Prédictive** :
    *   **Arbre de décision** : Pour classifier ou prédire des niveaux de fréquentation.
    *   **Séries Temporelles (ARIMA)** : Pour la prévision de la fréquentation future basée sur l'historique.
    *   **Régression Linéaire** : Pour identifier les facteurs influençant la fréquentation.
4.  **Reporting** : Création d'un rapport Power BI interactif pour la restitution des résultats.

## Méthodologie et Technologies

Le projet s'appuie sur une stack Data Science Python standard ainsi que sur des outils de Business Intelligence.

### Langages et Outils
*   **Python** : Langage principal pour l'analyse et la modélisation.
*   **Jupyter Notebook** : Environnement de développement.
*   **Power BI** : Outil de visualisation et de reporting.

### Bibliothèques Python utilisées
Les principales bibliothèques utilisées dans le notebook `datathon Victor .ipynb` sont :
*   **Pandas** : Manipulation et analyse des données (DataFrames, gestion des dates).
*   **Matplotlib** : Création de graphiques et visualisations (Box plots, courbes).
*   **Scikit-learn** :
    *   `PCA` : Analyse en Composantes Principales.
    *   `StandardScaler` : Normalisation des données.
    *   `train_test_split` : Séparation des jeux de données d'entraînement et de test.
    *   `LinearRegression` : Modèles de régression.
    *   `metrics` : Évaluation des modèles (MSE, R2).
*   **Statsmodels** :
    *   `ARIMA` : Modélisation de séries temporelles.
*   **Numpy** : Calcul numérique.

## Structure du Projet

*   `datathon Victor .ipynb` : Le notebook Jupyter contenant l'intégralité du code Python, de l'import des données à la modélisation.
*   `README.md` : Ce fichier de documentation.
*   *(Note : Le fichier de données source `Fréquentation journalière 2022-2023.xlsx` est référencé dans le code mais n'est pas inclus dans ce dépôt pour des raisons de confidentialité ou de taille).*

## Auteurs
*   Projet réalisé en groupe de 5
