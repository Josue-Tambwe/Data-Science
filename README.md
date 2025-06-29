# Data-Science
Projet introductif au domaine de la data science, de l'analyse et la visualisation des données avec Python. 
## Prérequis : 
Dans ce projet, sont considérées comme acquises certaines notions de base de la programmation, notamment les **variables** ainsi que leurs **types**, des structures des données telles que les listes, dictionnaires, etc...Les structures de branchement (**if**, **else**), les structures itératives (boucles **for**, **while**), le paradigme de la **Programmation Orientié Objet** (P.O.O), dans le langage de programmation qu'est Python.

## Notions abordées : 
### 1. *Numpy* : 
présentation du module Numpy pour les calculs vectoriel et matriciel, avec des méthodes les plus utilisées.
### 2. *Pandas* : 
Il s'agit d'une bibliothèque construite à partir de Numpy et fournit une implémentation éfficace des ***séries*** et  ***dataframe***. Cette bibliothèque apporte un avantage dans **l'étiquetage des données** que n'offre pas Numpy.
### 3. *Matplotlib* :
Pour la visualisation des données (data visualization), notamment les graphes des fonctions, les histogrammes, diagrammes etc... 
Ce package est compatible avec les tableaux de Numpy.
### 4. *Seaborn* : 
Dans le même ordre d'idées de la visualisation des donnnées, contrairement à la bibliothèque précédente (Matplotlib), Searborn est compatible avec la bibliothèque Pandas (pour les données étiquettées : séries et dataframes) et permet la réalisation des graphiques aussi pertinantes qu'agréables tout en réduisant les instructions généralement en **une seule ligne de code** (plus compacte), où Matplotlib en  nécessitait plusieurs.  
### 5. Apprentissage Supervisé : 
1. Bank_loan : modèle de classification qui consiste à prédire le statut d'**attribution** ou **non** d'un prêt bancaire à un individu. Une partie (preprocessing) est consacrée à la prépartation des données et aux analyses univariée et bivariée des variables.Les algorithmes utilisés sont **K-Nearest Neighbors** et La **régression logistique**. 
2. Cordiovascular_desease : modèle de **régression logistique** pour la prédiction de la présence  (ou non) d'une maladie cariovasculaire chez un patient, dans un premier temps en fixant un seuil par défaut de **0.5**, où toute prédiction de probabilité supérieure à ce seuil classifie le patient comme malade. Puis dans un second temps, un seuil optimal est fixé grâce à la méthode de **Youden**.
