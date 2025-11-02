# Analyse des Ventes 2019 et Dashboard Interactif avec Power BI

![Dashboard Interactif](dashboard_interactif.gif)

## 🎯 Objectif du Projet

Ce projet analyse un jeu de données de ventes pour l'année 2019 afin d'identifier les principaux indicateurs de performance et de répondre à des questions commerciales clés. Le but final est de consolider ces analyses dans un dashboard Power BI interactif et esthétique, permettant une exploration dynamique des données.

---

## 🛠️ Processus de Réalisation

Le projet a été mené en 4 grandes étapes :

1.  **Nettoyage et Préparation des Données (Python)**
    *   Utilisation de la bibliothèque **Pandas** dans un notebook Jupyter pour fusionner plusieurs fichiers CSV.
    *   Gestion des valeurs manquantes, correction des types de données (textes, nombres, dates).
    *   Création de nouvelles colonnes (`Chiffre_d'affaire`, `Mois`, `Heure`, `Ville`) pour enrichir l'analyse.

2.  **Analyse Exploratoire des Données (Python)**
    *   Utilisation de **Plotly Express** pour visualiser les tendances et répondre aux questions suivantes :
        *   Quel mois a généré le plus de chiffre d'affaires ?
        *   Quelle ville a enregistré le plus de commandes ?
        *   À quelles heures les ventes sont-elles les plus élevées ?
        *   Quels sont les produits les plus vendus et quel est le lien avec leur prix ?
        *   Quelles sont les combinaisons de produits les plus fréquentes ?

3.  **Création du Dashboard (Power BI)**
    *   Importation du jeu de données nettoyé (`.csv`) dans Power BI.
    *   Transformation finale des données dans l'éditeur Power Query (gestion des types de données et des paramètres régionaux).
    *   Création de visuels pour chaque analyse clé : histogramme, carte, graphique en courbes, graphique combiné et anneau.

4.  **Design et Interactivité**
    *   Mise en place d'un design moderne et cohérent (thème, couleurs, arrière-plan).
    *   Ajout d'indicateurs de performance clés (KPIs) pour une vue d'ensemble.
    *   Intégration de filtres (segments) pour permettre une exploration dynamique par ville et par mois.

---

## 🚀 Principaux Insights

L'analyse a révélé plusieurs informations stratégiques :

*   📈 **Saisonnalité :** Les ventes atteignent un pic significatif en **Décembre**, probablement en raison des fêtes de fin d'année.
*   🏙️ **Géographie :** **San Francisco** est le marché le plus important, suivi de Los Angeles et New York.
*   ⏰ **Timing :** Les pics d'activité des commandes se situent autour de **midi (12h)** et surtout en début de soirée vers **19h**, ce qui suggère les meilleurs moments pour des campagnes publicitaires.
*   🔗 **Ventes Croisées :** Les combinaisons les plus populaires sont l'achat d'un smartphone (iPhone, Google Phone) avec son câble de chargement, ce qui représente une excellente opportunité de ventes groupées (bundling).

---

## 🔧 Outils Utilisés

*   **Langage :** Python 3
*   **Bibliothèques :** Pandas, Plotly Express
*   **Outil de BI :** Microsoft Power BI
*   **IDE :** Jupyter Notebook (via VS Code)

---

![Dashboard Interactif](![alt text](<Dashboard interacitf.gif>))