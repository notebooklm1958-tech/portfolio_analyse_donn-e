# portfolio_analyse_donn-e


L'objectif est de construire un projet de portfolio puissant dans le domaine du **Trading / Finance** en utilisant la synergie de 4 outils majeurs : **Python, R, SQL, et Power BI**.

---

## 🎯 L'Objectif du Portfolio

Démontrer votre capacité à prendre des données financières brutes, à les nettoyer, à les analyser sous un angle statistique et business, puis à les restituer sous forme de tableau de bord interactif pour un recruteur.

* **Le jeu de données choisi :** Données boursières historiques (**OHLCV** : *Date, Open, High, Low, Close, Volume*).
* **La source exacte :** **Yahoo Finance** (Téléchargement gratuit en format CSV via l'onglet "Données historiques" d'une action comme Apple, LVMH ou TotalEnergies).

---

## 📅 Plan de Travail Chronologique (Sur 3 Mois)

### ⚙️ Mois 1 : Récupération, Nettoyage & Statistique (Python + R)

* **Semaine 1-2 (Python / Pandas) : Ingestion et Nettoyage**
* Téléchargement des fichiers CSV sur Yahoo Finance.
* Utilisation de Python pour vérifier les valeurs manquantes, formater les dates et ajouter une colonne `Ticker` (le nom de l'action) pour centraliser les données.


* **Semaine 3-4 (R / ggplot2) : Analyse Statistique & Exploration**
* Étude de la volatilité et de la distribution des rendements des actions.
* Création de graphiques de corrélation de niveau scientifique avec `ggplot2` pour voir comment les actions bougent les unes par rapport aux autres.



### 🗄️ Mois 2 : Stockage, Requêtes & Visualisation (SQL + Power BI)

* **Semaine 5-6 (SQL) : Modélisation et Calculs Financiers**
* Création de la table `trading_data` avec les bons types de données (`NUMERIC`, `DATE`, `BIGINT`).
* Importation des données nettoyées dans la base de données.
* Écriture de requêtes complexes (Window Functions : `LAG`, `OVER`) pour calculer les rendements journaliers et les moyennes mobiles (SMA 20/50 jours).


* **Semaine 7-8 (Power BI) : Création du Dashboard**
* Connexion de Power BI à la base de données SQL.
* Création de graphiques en bougies (Candlestick charts) et courbes de tendances.
* Mise en place de filtres interactifs pour rendre le rapport dynamique.



### 🚀 Mois 3 : Valorisation & Intégration au CV

* **Semaine 9-10 (GitHub) : Documentation du Projet**
* Création d'un dépôt GitHub pour le projet.
* Rédaction d'un fichier `README.md` soigné contenant : le contexte du projet, les scripts Python/R, les requêtes SQL, et des captures d'écran de votre dashboard Power BI.


* **Semaine 11-12 (CV) : Optimisation pour les recruteurs**
* Ajout du lien de votre portfolio en haut de votre CV.
* Formulation de vos puces de CV orientées "impact" (ex: *"Développement d'un pipeline data de bout en bout pour l'analyse de marchés financiers en combinant SQL, Python, R et Power BI"*).



---

## 🛠️ Récapitulatif de la chaîne de valeur des outils

1. **Python (Pandas) :** Le "Nettoyeur" ➔ Il prépare et standardise la donnée brute.
2. **R (Tidyverse/ggplot2) :** L' "Analyste Scientifique" ➔ Il étudie les statistiques et les corrélations.
3. **SQL (PostgreSQL/MySQL) :** Le "Gestionnaire" ➔ Il stocke proprement et calcule les indicateurs clés rapidement.
4. **Power BI :** Le "Communicant" ➔ Il transforme les chiffres en décisions visuelles pour les managers.

Vous avez désormais une feuille de route claire et extrêmement valorisante pour votre profil !
