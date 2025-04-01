Ce projet a pour objectif de développer et d'évaluer deux types de modèles d'apprentissage automatique : un arbre de décision 
et un réseau de neurones artificiels. L'objectif est de traiter des données synthétiques fournies et de les utiliser pour entraîner 
les modèles, puis de les évaluer sur des métriques classiques telles que l'exactitude, la précision, le rappel et le F1-score. 
Le projet est divisé en quatre parties distinctes, permettant de tester et d'analyser les performances des modèles à chaque étape.
----------
Structure du Projet:

1)Préparation des données
  
  -Les données sont fournies sous forme d'un fichier CSV généré à l'aide de Sklearn.
  
  -20 % des données sont séparées pour servir de jeu de test.
  
  -Le travail de préparation inclut la normalisation, l'encodage en one-hot si nécessaire, et la séparation en jeux d'entraînement et de test.

2)Mise en œuvre des modèles

  -Arbre de décision : Le modèle sera formé en utilisant des quartiles pour discrétiser les attributs et calculer les gains d'information.
  
  -Réseaux de neurones artificiels : Plusieurs architectures avec des activations tanh et ReLU seront testées, avec un entraînement par mini-batchs 
  et un mécanisme d'early stopping pour éviter le sur-apprentissage.

3)Analyse des modèles

  -Des métriques de classification détaillées seront calculées pour chaque modèle, et une matrice de confusion sera générée pour évaluer la qualité 
  des prédictions sur chaque classe.
  
4)Sélection du meilleur modèle
  
  -Les performances des modèles seront comparées pour déterminer celui qui offre les meilleurs résultats en fonction des critères définis dans le projet.

----------
Méthodologie
Arbre de décision :

  -Calcul de l'entropie d'une partition.
  
  -Calcul du gain d'une partition.
  
  -Détermination du meilleur partitionnement.

Réseaux de neurones :

  -Mise en œuvre d'une passe avant avec une instance.
  
  -Mise en œuvre de la rétropropagation et mise à jour après une passe avant.

Calcul des métriques :

  -Calcul de l'exactitude, précision, rappel, et F1-score pour chaque classe.
  
  -Construction des matrices de confusion pour chaque modèle.
