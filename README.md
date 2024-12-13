# README - DATACAMP (Groupe 3) : Analyse de ressenti sur le film *Wicked*

---

## 🧑‍🤝‍🧑 Participants

- Chléo Hinn
- Khalil Djahel
- Marius Ozanne
- Bryan Bontrain

---

## 🎥 Description du projet

Ce projet a pour objectif d’analyser le ressenti des spectateurs concernant le film *Wicked*. En exploitant les critiques et les notes disponibles sur IMDb, nous souhaitons détecter les émotions et les tendances d’opinion exprimées par les utilisateurs. Les résultats seront présentés sous forme de visualisations pour une interprétation claire et intuitive.

---

## 🎯 Objectifs

- Collecter et nettoyer les données des critiques et des notes IMDb.
- Analyser les sentiments (émotions positives, neutres, négatives) dans les commentaires.
- Présenter les résultats via des visualisations interactives.


---

## ✨ Fonctionnalités

1. **Extraction et préparation des données**

   - Collecte des critiques et des notes via web scraping de IMDb.
   - Nettoyage des données pour éliminer les entrées non pertinentes.

2. **Analyse des sentiments**

   - Classification des émotions positives, neutres et négatives.
   - Analyse thématique pour identifier les points saillants.

3. **Visualisation des résultats**

   - Graphiques interactifs (distribution des sentiments, mots-clés dominants).
   - Tableau de bord synthétique.

---

## 🗂️ Étapes du projet

1. **Collecte des données** : Récupération des critiques IMDb.
2. **Nettoyage des données** : Élimination des doublons et standardisation.
3. **Analyse des sentiments** : Utilisation d’algorithmes NLP pour la classification.
4. **Visualisation** : Présentation des résultats via des outils comme Matplotlib ou Tableau.

---

## 🔧 Prérequis

Les prérequis sont tous installés grace au fichier requirements, mais voici les principaux :
- **Langages** : Python 3.9+
- **Bibliothèques Python** :
  - BeautifulSoup (Web Scraping)
  - Selenium (Scrapping)
  - Pandas (Traitement des données)
  - NLTK et TextBlob (pour l’analyse des sentiments)
- **Outils supplémentaires** : Streamlit (Cloud et Visualisation).

---

## 🚀 Installation

1. Clonez le dépôt ou acceder au zip fournit :
   ```bash
   git clone https://github.com/brillant972/EFREI_M1_Datacamp.git
   ```
2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```
3. Lancement du script via Streamlit (dans votre CMD) :
   ```bash
   streamlit run imdb_sentiment_app.py
   ```
   

