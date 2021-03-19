# Pandas



## Dans les grandes lignes

* Bibliothèque de manipulation de données couplée à numpy
* Fournit des structures de données de haut niveau
* Facilite la manipulation des tableaux au travers des DataFrames 2D ou les Panels 3D
* Sans indexes, ralentit fortement l’exécution du programme au profit de la rapidité de développement
* S’appuie fortement sur les indexes pour les fonctions avancées (séries temporelles et groupes)

## Notes

* La notion de datasets est similaire à la notion de feuille excel ou table SQL
* Pandas peut être vue comme un mini ETL (il permet même de fournir la mémoire utiliser par dataframe!)
* Numpy est omniprésent dans Pandas, ce dernier l’étend pour faciliter son utilisation => la syntax des masked array de numpy est donc compatible
* Particulièrement adapté à la transformation de donnée et les séries temporelles
* Possède une documentation riches 

## Structure

* Les Séries
  - Une liste ordonnée
  - Les « colonnes » peuvent être nommées
  - ___Indexé___
* Les DataFrames
  - Tableau de données
  - Colonnes nommées
  - Permettant la manipulation de masse
  - ___Indexé___


## Astuces

* Penser à configurer le nombre de lignes et colonnes en sorties voulues (et éviter de ne pas mettre de limite  sous peine de faire planter votre ide/navigateur)

* Que ce soit avec les dataframes ou les series, vous pouvez toujours revenir à numpy avec la fonctions xxx.values
* Attention, en retournant sur numpy, vous perdez les indexes (y compris dans les tableaux renvoyés)
