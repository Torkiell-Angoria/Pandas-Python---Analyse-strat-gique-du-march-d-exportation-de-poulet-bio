# Analyse stratégique du marché d'exportation du poulet bio

##  Objectifs du projet

Ce projet a pour but de **segmenter les pays** à l’échelle mondiale afin d’identifier les zones géographiques les plus pertinentes pour **exporter les produits avicoles** de l’entreprise "La Poule qui Chante".

Les étapes du projet sont les suivantes :

- Collecte de données issues de **sources ouvertes** : FAO, Banque Mondiale, Données Mondiales.
- Enrichissement du jeu de données via une **analyse PESTEL**, avec un minimum de **8 variables pertinentes**.
- Préparation, nettoyage et fusion des données pour constituer une base cohérente.
- Analyse exploratoire des données.
- **Réduction de dimension par ACP** (Analyse en Composantes Principales).
- **Clustering des pays** à l’aide de la Classification Ascendante Hiérarchique (CAH) et du K-means.
- Interprétation des résultats pour guider la stratégie d’exportation.

---

## 🧰 Outils et technologies utilisés

| Outil / Technologie | Rôle |
|----------------------|------|
| **Python**           | Langage principal pour tout le projet |
| **Pandas**           | Manipulation et nettoyage des données |
| **Matplotlib / Seaborn / Plotly** | Visualisations |
| **Scikit-learn**     | ACP, K-Means, évaluation des clusters |
| **Scipy**            | Classification ascendante hiérarchique (CAH) |
| **Jupyter Notebook** | Documentation et exécution du code |

---

## 📦 Livrables à rendre (dans un dossier `.zip`)

Le dossier compressé à rendre contient les **fichiers suivants** :

### 1. 📁 `1_data_cleaning.ipynb`
- Préparation, nettoyage et fusion des données
- Justification des variables retenues (analyse PESTEL)
- Résultat : jeu de données prêt à l’analyse (≥100 pays, ≥8 variables)

- ![Nettoyage](https://github.com/Torkiell-Angoria/Pandas-Python---Analyse-strat-gique-du-march-d-exportation-de-poulet-bio/blob/main/img/acp.gif)

### 2. 📁 `2_analysis_clustering.ipynb`
- Analyse exploratoire (visualisations, stats descriptives)
- ACP : cercle des corrélations, projection des pays
- Clustering : CAH + K-Means
- Interprétation des groupes formés

![ACP](https://github.com/Torkiell-Angoria/Pandas-Python---Analyse-strat-gique-du-march-d-exportation-de-poulet-bio/blob/main/img/nettoyage.gif)

### 3. 📁 `presentation_COMEX.pptx` (ou `.pdf`)
- Présentation synthétique destinée au **COMEX**
- Maximum **25 slides**
- Contenu : objectifs, méthodologie, visualisations clés, recommandations stratégiques

![Presentation](https://github.com/Torkiell-Angoria/Pandas-Python---Analyse-strat-gique-du-march-d-exportation-de-poulet-bio/blob/main/img/pr%C3%A9sentation.gif)


## Carte des clients potentiels

![Carte client potentiels](https://github.com/Torkiell-Angoria/Pandas-Python---Analyse-strat-gique-du-march-d-exportation-de-poulet-bio/blob/main/img/projet%2011%20segmentation%20clients.PNG)
