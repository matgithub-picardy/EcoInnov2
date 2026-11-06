# Économie de l'innovation : notebooks Python

Notebooks du cours de M1 Économie de l'innovation (Management de l'innovation, Université de Picardie Jules Verne).

[![Ouvrir dans MyBinder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/COMPTE/DEPOT/HEAD)

Remplacez `COMPTE` et `DEPOT` par le nom du compte GitHub et celui du dépôt.

## Ouvrir les notebooks

**Sans installation.** Cliquez sur le bouton MyBinder ci-dessus. Le premier lancement peut prendre quelques minutes. Rien n'est conservé : téléchargez votre notebook (menu File, Download) avant de fermer l'onglet.

**Sur votre ordinateur.** Installez Anaconda (anaconda.com), qui contient Python, Jupyter et les bibliothèques utilisées. Téléchargez le dépôt (bouton Code, Download ZIP), décompressez-le et ouvrez les notebooks avec Jupyter. Gardez le dossier `donnees` à côté des notebooks.

## Le parcours

Avancez à votre rythme. Le parcours Python est facultatif si vous connaissez déjà le langage.

| Notebook | Contenu |
|---|---|
| **Parcours Python** | |
| `python-1-jupyter.ipynb` | utiliser un notebook Jupyter |
| `python-2-variables-et-calculs.ipynb` | variables, calculs et textes |
| `python-3-conditions-et-boucles.ipynb` | conditions et boucles |
| `python-4-listes-et-dictionnaires.ipynb` | listes, tuples et dictionnaires |
| `python-5-fonctions.ipynb` | découpages et fonctions |
| **TD** | |
| `td-1-decouvrir-une-base.ipynb` | premiers pas en Python et découverte d'une base |
| `td-2-recuperer-et-preparer-une-base.ipynb` | récupérer et préparer une base |
| `td-3-statistiques-descriptives.ipynb` | statistiques descriptives et comparaisons |
| `td-4-de-la-description-a-la-question.ipynb` | de la description à la question |
| **Ateliers complémentaires (facultatifs)** | |
| `atelier-a-rd-europe.ipynb` | l'effort de R&D en Europe (données par API) |
| `atelier-b-diffusion-mobile.ipynb` | la diffusion du téléphone mobile (données par API) |

Dans les TD, chaque partie porte un niveau. Les parties **Essentiel** suffisent pour le projet. Les parties **Pour aller plus loin** et **Bonus** présentent des outils plus avancés (régression, effets fixes, probit, téléchargement direct). Les utiliser est un plus. Ne pas les utiliser n'est jamais pénalisé.

## Les données

Le dossier `donnees` contient trois fichiers tirés des World Development Indicators de la Banque mondiale (19 pays, 2000-2023). Leurs variables sont décrites dans `donnees/LISEZMOI.md`.

## Bibliothèques

`requirements.txt` liste les bibliothèques installées par MyBinder : pandas, matplotlib, statsmodels et scipy.
