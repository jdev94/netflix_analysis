#  Analyse Netflix - Data Cleaning

Projet d'apprentissage focalisé sur le nettoyage et la manipulation de données avec pandas. Transformation d'un dataset brut de 8809 titres Netflix en données structurées prêtes pour l'analyse.

>**Version 1.0** - Focus sur le data cleaning. Les visualisations seront ajoutées en v2.0 pour montrer ma progression.

## Technologies

**Python** • **pandas** • **numpy** • **Jupyter Notebook**

### Data Cleaning
-  Résolution problème d'encodage (latin-1)
-  Conversion `date_added` en datetime
-  Séparation colonne `duration` (films: minutes | séries: saisons)
-  Normalisation colonnes multi-valuées avec `.explode()`
-  Création features temporelles (année, mois, jour semaine)

### Analyse Exploratoire
Réponses à 10 questions business :
- Composition catalogue (69.6% films, 30.4% séries)
- Tendances temporelles (pic 2019: 1999 ajouts)
- Top catégorie: International Movies (2624 titres)
- Acteur US le plus présent: Adam Sandler (20 films)
- Durée moyenne films: 99.6 min | Séries: 1.76 saisons

## Compétences démontrées

**Data Cleaning** • **Feature Engineering** • **Pandas avancé** (`.explode()`, `.dt`, `.loc[]`) • **Organisation ETL** • **Documentation**

## Prochaines étapes

- Ajouter visualisations (matplotlib/seaborn)
- Créer dashboard interactif
- Appliquer Machine Learning

## Contact

**Audinot Jonathan**  
jdev.pro@outlook.fr
www.linkedin.com/in/jonathan-audinot

---

*Projet d'apprentissage - Janvier 2026*
