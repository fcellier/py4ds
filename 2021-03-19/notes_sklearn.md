# SKLearn

## En deux mots
* Très très grande bibliothèque de machine learning
* S’articule autour de 3 familles algorithmiques :
    - Classification
    - Regression
    - Clustering

* Et 3 ‘outils’ pour la variété et qualité des modèles
    - Sélection des entrées
    - Sélection des modèles
    - Transformation des entrées

[Quel algo choisir?](https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html)

## Gardez en tête
* Pas de sauvegarde de modèle par un format standard (pickle de python mais très proche de l’implémentation de python et sa version). Pensez donc à des solutions alternatives comme bentoML
* La plupart des algorithmes (surtout ensembliste) sont lents pour des réponses unitaires (avec de bonne performances en mode batch)
* Attention à ne pas vous noyer : Dans python il y a toujours une méthode ou fonction a privilégier. Dans sklearn, il existe très souvent un nombre impressionnant de solution pour résoudre le même problème
