# Analyse de la volatilité d'un indice financier : cas du S&P 500

## Présentation

Ce projet porte sur l'étude de la volatilité d'un indice financier à partir de ses données historiques.

J'ai utilisé Python pour calculer les rendements journaliers, mesurer la volatilité sur différentes fenêtres et représenter les résultats avec des graphiques.

Ce travail m'a permis de mettre en pratique des notions d'analyse de données, de statistiques descriptives et d'analyse financière.

## Objectifs

Les objectifs du projet sont les suivants :

- Calculer les rendements journaliers.
- Mesurer la volatilité historique.
- Comparer des fenêtres glissantes de 20 et 60 jours.
- Annualiser la volatilité.
- Représenter l'évolution de la volatilité.
- Étudier le lien entre la volatilité et l'amplitude des rendements.

## Concepts théoriques

Le rendement mesure la variation du prix entre deux jours.

La volatilité mesure la dispersion des rendements. Dans ce projet, elle est calculée à partir de l'écart-type des rendements sur des fenêtres glissantes de 20 jours et de 60 jours.

Une fenêtre de 20 jours réagit plus rapidement aux changements récents, tandis qu'une fenêtre de 60 jours donne une évolution plus lissée et progressive.

La volatilité a été annualisée avec une approximation basée sur 252 jours de cotation boursière par an.

La corrélation a été utilisée pour étudier la relation entre la volatilité et l'amplitude des rendements. Elle permet d'observer une relation, mais ne prouve pas qu'une variable est la cause de l'autre.

## Données utilisées

Les données correspondent aux prix historiques de l'indice S&P 500.

Elles ont été récupérées avec la bibliothèque `yfinance`. Les prix de clôture ont ensuite été utilisés pour calculer les rendements journaliers.

## Méthode

J'ai d'abord récupéré, exploré et observé les données historiques.

J'ai ensuite calculé les rendements journaliers à partir des prix de clôture.

La volatilité historique a été calculée avec l'écart-type sur des fenêtres glissantes de 20 et de 60 jours.

Enfin, j'ai représenté les résultats avec des graphiques et comparé la volatilité avec l'amplitude absolue des rendements.

## Outils utilisés

- Python
- Jupyter Notebook
- pandas
- yfinance
- matplotlib

## Résultats

La volatilité varie selon les périodes étudiées.

La fenêtre de 20 jours réagit plus rapidement aux changements du marché que la fenêtre de 60 jours.

La comparaison avec l'amplitude absolue des rendements montre une relation positive, mais limitée.

Les résultats détaillés, les calculs et les graphiques sont disponibles dans le notebook et dans les fichiers HTML et PDF.

## Reproduction de l'analyse

Pour reproduire l'analyse :

1. Installer les bibliothèques nécessaires.
2. Ouvrir le notebook `premier projet.ipynb`.
3. Exécuter les cellules dans l'ordre.
4. Vérifier les tableaux et les graphiques obtenus.

## Limites

Cette analyse porte sur un seul indice et sur une période donnée.

La volatilité historique décrit les variations passées, mais ne permet pas de prévoir exactement les variations futures.

Les résultats peuvent également changer selon l'indice étudié, la période choisie et la taille de la fenêtre utilisée.

## Fichiers du projet

- `premier projet.ipynb` : notebook contenant le code, les calculs et les graphiques.
- `analyse_volatilite_finale.csv` : données et résultats exportés depuis le notebook.
- `Projet_1_S&P500_corrigé.html` : version HTML du notebook.
- `premier projet.pdf` : version PDF du notebook.

 ## Source des données

Les données historiques ont été récupérées avec la bibliothèque `yfinance`.

Le symbole utilisé pour le S&P 500 est `^GSPC`.

## Avertissement

Ce projet est réalisé dans un cadre pédagogique. Les résultats présentés ne constituent pas un conseil en investissement et ne permettent pas de prévoir avec certitude les performances futures du marché.

## Conclusion

Ce projet constitue une première mise en pratique de Python pour l'analyse quantitative de données financières.

Il m'a permis de mieux comprendre le calcul de la volatilité, l'utilisation des fenêtres glissantes et l'interprétation de résultats statistiques.

## Auteur

- Nom : Hayana
- Formation : Master 2 en Probabilités, Statistique et Finance
- Établissement : Université de Yaoundé 1
- Année : 2026
