# Ter Graphes de citations pour la recherche de citation 

_Plusieurs notebooks afin de générer des graphes de citation depuis des articles scientifique arXiv_

# Dataset de travail - Génération de graphe de citation

Ce repository contient le dataset de travail utilisé pour notre projet de recherche sur la génération de graphe de citation pour la recherche d'informations scientifiques.

## Contenu du dataset

Le dataset est construit à partir d'un corpus d'articles scientifiques au format PDF. Chaque exemple du dataset comprend les informations suivantes :

- ID : l'identifiant numérique unique de l'article
- Title : le titre de l'article
- citation_contexts: Les citation dans le texte de l'article
- Abstract : le résumé de l'article
- Categories : la catégorie à laquelle appartient l'article

## Structure du repository

- `dataset.csv` : le fichier CSV contenant les données du dataset
- `intersection.ipynb` : un notebook Jupyter afin de réaliser l'intersection des datasets source
- `etude_des_datasets.ipynb` : un notebook Jupyter décrivant les étapes de préparation du dataset
- `Graphe_de_citation.ipynb` : un notebook Jupyter pour génerer le graphe de citation d'un ou plusieurs articles
- `articletest.pdf` : un article sientifique de 'test' pour le notebook `Graphe_de_citation.ipynb`
- `article_TER` : notre article scientifique décrivant notre démarche

## Téléchargement du dataset

Le fichier CSV contenant les données du dataset peut être téléchargé à partir de l'URL suivante :

[URL du fichier CSV](https://uncloud.univ-nantes.fr/index.php/s/JG27sq6kZ4zSztL)

## Utilisation du dataset


Le fichier `dataset.csv` peut être utilisé pour entraîner des modèles de classification de catégories d'articles scientifiques ou pour mener des analyses et des études dans le domaine de la recherche d'informations scientifiques.

Pour utiliser le dataset, vous pouvez charger le fichier CSV dans votre environnement de programmation préféré et accéder aux différentes colonnes pour les utiliser dans vos tâches de traitement de texte.

## Citation

Si vous utilisez ce dataset dans votre recherche ou vos projets, nous vous encourageons à citer notre article disponible dans ce repository `article_TER.pdf`.


# Contributors

Pour toute question ou commentaire, n'hésitez pas à nous contacter :

|                                                    |                  |
| -------------------------------------------------- | ---------------- |
| [@MangoHiller](https://github.com/MangoHiller)     | Hugo LEGUILLIER  |
| [@miranovic](https://github.com/miranovic)         | Imran NAAR       |
