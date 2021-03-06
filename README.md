

# Introduction au langage Python pour l'analyse de données

*Auteur: Mickaël Tits, CETIC asbl, mickael.tits@cetic.be*

Ce cours, à la fois minimaliste et pratique, vous permettra :

* de découvrir rapidement les concepts essentiels de la programmation en **Python**,
* d'apprendre à maîtriser les librairies les plus utilisées pour l'analyse de données (**Data Science**),
* et de vous familiariser avec les concepts fondamentaux de l'apprentissage automatique (**Machine Learning**). 

Ce cours s'addresse donc principalement aux personnes désireuses de rapidement mettre le pied à l'étrier dans ce domaine passionnant, ou à toute personne dont l'activité professionnelle, liée de près ou de loin aux sciences des données, nécessite d'avoir un aperçu concret de ce domaine et de ce qu'il permet de faire.

## Chapitres dans Google Colab

Chaque chapitre, entièrement contenu dans un **notebook iPython (Jupyter)**, est directement accessible sur la plateforme **[Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb)**. Google Colab est une plateforme cloud entièrement gratuite, donnant un accès direct et facile à un une interface de programmation en Python (via des notebooks Jupyter) déjà correctement pré-configurée, et disposant de nombreuses librairies pré-installées. Chaque utilisateur (connecté à un compte Google) peut disposer d'une machine virtuelle temporaire en ligne, lui permettant d'exécuter des Notebooks directement à partir d'une page Web, d'enregistrer ces Notebooks dans Google Drive, et de les partager aussi facilement qu'un autre document cloud (cfr Google Docs ou Google Sheet).


0. [Premier notebook iPython dans Google Colab](https://colab.research.google.com/github/titsitits/Python_Data_Science/blob/master/0_Premier_Notebook.ipynb)
1. [Introduction au langage de programmation Python](https://colab.research.google.com/github/titsitits/Python_Data_Science/blob/master/1_Introduction.ipynb)
2. [Les collections d'objets Python](https://colab.research.google.com/github/titsitits/Python_Data_Science/blob/master/2_Collections.ipynb)
3. [Concepts avancés de programmation: exceptions, fonctions, objets](https://colab.research.google.com/github/titsitits/Python_Data_Science/blob/master/3_Advanced_Python.ipynb)
4. [Un exemple concret: analysons quelques biens immobiliers...](https://colab.research.google.com/github/titsitits/Python_Data_Science/blob/master/4_Example.ipynb)
5. [Les librairies Python pour l'analyse de données](https://colab.research.google.com/github/titsitits/Python_Data_Science/blob/master/5_Python_packages.ipynb)
6. [Introduction au Data Mining et à la visualisation de données](https://colab.research.google.com/github/titsitits/Python_Data_Science/blob/master/6_Data_Mining.ipynb)
7. [Introduction au Machine Learning](https://colab.research.google.com/github/titsitits/Python_Data_Science/blob/master/7_Machine_Learning_Introduction.ipynb)
8. [Un exemple concret: estimation du prix d'une maison à Ames (Iowa, USA)](https://colab.research.google.com/github/titsitits/Python_Data_Science/blob/master/8_Example_Ames_Housing_Dataset.ipynb)

## Chapitres en lecture seule

Les notebooks peuvent être visualisés simplement grâce à nbviewer:

### Notebooks non-exécutés

1. [Introduction au langage de programmation Python](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/1_Introduction.ipynb)
2. [Les collections d'objets Python](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/2_Collections.ipynb)
3. [Concepts avancés de programmation: exceptions, fonctions, objets](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/3_Advanced_Python.ipynb)
4. [Un exemple concret: analysons quelques biens immobiliers...](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/4_Example.ipynb)
5. [Les librairies Python pour l'analyse de données](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/5_Python_packages.ipynb)
6. [Introduction au Data Mining et à la visualisation de données](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/6_Data_Mining.ipynb)
7. [Introduction au Machine Learning](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/7_Machine_Learning_Introduction.ipynb)
8. [Un exemple concret: estimation du prix d'une maison à Ames (Iowa, USA)](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/8_Example_Ames_Housing_Dataset.ipynb)

### Notebooks exécutés (avec les résultats des cellules):

1. [Introduction au langage de programmation Python](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/Completed_notebooks/1_Introduction.ipynb)
2. [Les collections d'objets Python](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/Completed_notebooks/2_Collections.ipynb)
3. [Concepts avancés de programmation: exceptions, fonctions, objets](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/Completed_notebooks/3_Advanced_Python.ipynb)
4. [Un exemple concret: analysons quelques biens immobiliers...](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/Completed_notebooks/4_Example.ipynb)
5. [Les librairies Python pour l'analyse de données](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/Completed_notebooks/5_Python_packages.ipynb)
6. [Introduction au Data Mining et à la visualisation de données](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/Completed_notebooks/6_Data_Mining.ipynb)
7. [Introduction au Machine Learning](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/Completed_notebooks/7_Machine_Learning_Introduction.ipynb)
8. [Un exemple concret: estimation du prix d'une maison à Ames (Iowa, USA)](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/Completed_notebooks/8_Example_Ames_Housing_Dataset.ipynb)

### Solutions des exercices
[Solutions des exercices](https://nbviewer.jupyter.org/github/titsitits/Python_Data_Science/blob/master/Exercise_Solutions.ipynb)


## Ressources supplémentaires

Pour aider l'étudiant au cours de son apprentissage, voici quelques ressources utiles:

[Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb) est un service donnant gratuitement accès à une machine virtuelle, disposant déjà d'un interpréteur Python et de nombreuses librairies préinstallées. Il permet de rapidement apprendre le Python sans s'encombrer de problématiques telles que les performances d'une machine locale et la gestion de l'interpréteur Python et de nombreuses librairies.

Pour installer Python localement, la distribution Anaconda est recommandée, ainsi que l'environnement Jupyter Lab : https://www.anaconda.com/distribution/

Les librairies Python utilisées dans ce cours, et en partitulier Pandas, disposent de très nombreuses méthodes. Bien qu'une requête sur un moteur de recherche permet d'obtenir vite une réponse à une question de programmation, il reste intéressant d'avoir une idée des possibilités et limitations de ces librairies. 
Pour Pandas, les méthodes les plus souvent utilisées sont les méthodes des objets [DataFrame](https://pandas.pydata.org/pandas-docs/stable/reference/frame.html), [Series](https://pandas.pydata.org/pandas-docs/stable/reference/series.html), et [GroupBy](https://pandas.pydata.org/pandas-docs/stable/reference/groupby.html). Toutes les librairies présentées se basent sur la librairie de calcul scientifique Numpy, et la plupart des opérations mathématiques dépendent de méthodes appliquées sur l'objet [N-dimensional Array (ndarray)](https://docs.scipy.org/doc/numpy/reference/arrays.ndarray.html).

## Références

Le jeu de données utilisé comme exemple dans le [Chapitre 8](https://colab.research.google.com/github/titsitits/Python_Data_Science/blob/master/8_Example_Ames_Housing_Dataset.ipynb) et est disponible sur [Kaggle](https://www.kaggle.com/c/home-data-for-ml-course).

*Copyright: CETIC asbl - 2019*
