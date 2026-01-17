# Analyse Netflix - Data Cleaning & Visualization

Projet d'apprentissage complet sur le nettoyage, manipulation et visualisation de données avec pandas et Plotly. Transformation d'un dataset brut de 8809 titres Netflix en insights business exploitables.

> **Version 2.0** - Data cleaning + visualisations interactives

## Technologies

**Python** • **pandas** • **numpy** • **Plotly Express** • **Jupyter Notebook**

### Data Cleaning
- Résolution problème d'encodage (latin-1)
- Conversion 'date_added' en datetime
- Séparation colonne 'duration' (films: minutes | séries: saisons)
- Normalisation colonnes multi-valuées avec '.explode()'
- Création features temporelles (année, mois, jour semaine)
- Fusion avec codes ISO-3 pour géolocalisation

### Analyse Exploratoire
Réponses à 10 questions business :
- Composition catalogue (69.6% films, 30.4% séries)
- Tendances temporelles (pic 2019: 1999 ajouts)
- Top catégorie: International Movies (2624 titres)
- Acteur US le plus présent: Adam Sandler (20 films)
- Durée moyenne films: 99.6 min | Séries: 1.76 saisons

### Visualisations Interactives

- **Tendances de production annuelle** : barplot groupé comparant Films vs Séries par année de sortie (1942-2021)
- **Rythme d'ajouts au catalogue** : série temporelle mensuelle avec moyenne mobile 6 mois (2008-2021)
- **Distribution durée films** : boxplot horizontal révélant médiane 99 min et outliers
- **Répartition des genres** : treemap hiérarchique de 40+ catégories (International Movies dominant à 14.2%)
- **Expansion géographique** : carte choropleth animée montrant l'évolution pays producteurs (3→50+ pays)

### Insights Business

- **Pic de production 2019** : 1999 ajouts suivi d'une chute COVID-2020
- **Tournant stratégique 2016** : explosion de la production locale (Inde, Corée du Sud, Brésil)
- **Concentration genres** : top 5 représente ~50% du catalogue
- **Glocalisation accélérée** : passage de 3-4 pays producteurs (2008) à 50+ (2021)
- **Domination américaine** : USA produit 300+ titres/an (marché domestique + infrastructures)

## Compétences démontrées

**Data Cleaning** • **Feature Engineering** • **Pandas avancé** • **Géovisualisation** • **Storytelling data** • **Lissage statistique** • **Documentation**

## Contact

**Audinot Jonathan**  
[jdev.pro@outlook.fr](mailto:jdev.pro@outlook.fr)
[www.linkedin.com/in/jonathan-audinot](https://www.linkedin.com/in/jonathan-audinot)

---

*Projet d'apprentissage - Janvier 2026*