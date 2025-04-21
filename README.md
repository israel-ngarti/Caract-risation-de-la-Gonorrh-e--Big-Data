# 🧬 Caractérisation de la Gonorrhée via Analyse Big Data

> Un projet de data science appliqué à la santé publique, visant à identifier les facteurs de risque de la gonorrhée à partir de données médicales.

## 📚 Description

Ce projet s'inscrit dans le cadre d’un devoir maison du cours de Big Data. Il a pour objectif d'analyser un jeu de données de patients afin de :
- Identifier les facteurs de risque associés à la gonorrhée
- Caractériser les groupes les plus exposés
- Proposer des pistes pour une meilleure stratégie de dépistage

Le jeu de données contient des informations telles que :
- Âge, sexe, état civil
- Orientation sexuelle
- Antécédents de MTS
- Nombre de partenaires
- Résultats de tests médicaux

## 🛠️ Méthodologie

1. **Nettoyage des données**
   - Identification et traitement des valeurs manquantes (99, 9, etc.)
   - Suppression ou imputation selon le type et la fréquence

2. **Catégorisation**
   - Regroupement des variables numériques en classes (âge, nombre de partenaires...)
   - Encodage one-hot

3. **Analyse statistique**
   - Tableaux croisés et test du chi-deux
   - Identification des variables significativement liées au diagnostic

4. **Modélisation**
   - Régression logistique
   - Analyse des odds ratios pour interprétation des facteurs de risque

## 📈 Résultats clés

- Les individus **de moins de 30 ans**, **ayant un nombre élevé de partenaires** et **homosexuels** présentent une probabilité plus élevée d’être diagnostiqués positifs.
- Les femmes et les personnes hétérosexuelles ont un **risque moindre**.
- Les antécédents de MTS ne sont **pas significativement associés** au diagnostic de gonorrhée dans ce jeu de données.

## 🧪 Technologies utilisées

- Python (pandas, matplotlib, statsmodels)
- Méthodes statistiques : Khi-deux, régression logistique, VIF


## 👥 Auteurs

- **MOIELWAY NGARTI Israël**  
- **Philia EZIN**

Année universitaire : 2024-2025

---

Merci pour votre lecture ! Pour toute suggestion ou remarque, n'hésitez pas à ouvrir une issue 
