# Réseau de Neurones
   
   # Algorithmes d'Adaline et Perceptron

# Premier partie :
On va générez un ensemble de données 2D qui est composé de deux classes (notées -1 et 1) linéairement séparables d’objets répartis uniformément. Pour chaque classe on génere 50 objets. Et pour les coordonnées x et y séparément on le combiner ensuite. et on va étiquetez les variables par «area» et «perimeter».

# Deuxième partie :
 1 - On considère un réseau de neurone de type *ADALINE*. On veut apprendre l’ensemble d'associations entre les données et les classes.
 2 - Une fonction err_adal permettant de calculer l’écart entre la sortie désirée (classe) et la sortie calculée par Adaline.
 3 - Une fonction grad_adal permettant de calculer une approximation du gradient.
 4 - Une fonction adapt_adal permettant de mettre à jour les poids des connexions dans Adaline en fonction du gradient.
 
Une fonction Adaline utilisant les fonctions précédentes permettant de faire un apprentissage du modèle Adaline sur la base de données générée précédemment. On utilisera la fonction de transition indiquée dans la figure ci-dessous, ainsi que les valeurs initiales des poids et un pas du gradient de ε=0.1.

# Troisème partie :
On va traiter les mêmes données avec cette fois un autre réseau de neurone *PERCEPTRON*.
	
