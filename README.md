# KPPV-RB
TP 4 : K-NN
 • Introduction:
 
En intelligence artificielle, plus précisément en apprentissage automatique, la méthode des k plus proches voisins est une méthode d’apprentissage supervisé. En abrégé k-NN ou KNN, de l'anglais k-nearest neighbors.
Dans ce cadre, on dispose d’une base de données d'apprentissage constituée de N couples
« entrée-sortie ». Pour estimer la sortie associée à une nouvelle entrée x, la méthode des k plus proches voisins consiste à prendre en compte (de façon identique) les k échantillons d'apprentissage dont l’entrée est la plus proche de la nouvelle entrée x, selon une distance à définir. Puisque cet algorithme est basé sur la distance, la normalisation peut améliorer sa précision.
• ObjectifduTP:
 
•
Dans ce TP on va implémenter K-NN sur un vrai jeu de données pour faire une classification multi-classes.
- Pour suivre ce TP il faut disposer de la bibliothèque Sickit-Learn.
On utilisera le célèbre jeu de données MNIST.
Scikit-Learn vient avec un ensemble de jeux de données prêt à l’emploi pour des fins d’expérimentations. Ces dataset sont regroupés dans le package sklearn.datasets Notre classificateur et dans : « sktlearn.neighbors »
Data set utiliser :
MNIST est une base de données étiquetée propice pour un apprentissage supervisé. Dans l’image ci-dessus, pour chaque chiffre, on a sa représentation sous forme d’image ainsi que son étiquette. Par exemple, pour le dernier chiffre en bas à droit, l’étiquette vaut 9 vu qu’il s’agit du chiffre 9. La représentation de ces chiffres est normalisée à travers tout le jeu de données MNIST. Ainsi, chaque chiffre est codé dans un format 8 pixels * 8 pixels. En plus, chaque pixel peut prendre une valeur de 0 à 255. Cette plage de valeurs représente le niveau de gris Grayscale. En d’autres terme, chaque représentation d’une image est une matrice de dimension.Le jeu de données MNIST présent par défaut dans la librairie Scikit Learn, comporte un sous-ensemble de la “vraie” base de données MNIST. Le sous-ensemble comporte chiffres que nous diviserons par la suite en deux sous ensembles : d’entrainement et de test.
 
1. Importation de librairies :
  2. Les Fonction utiliser dans le prétraitement :
    

 3. La Fonction Main:
   4. Le Test :
Après l’exécution on trouve l’interface suivante :
  

On clique sur apprentissage on obtient le message suivant dans le Console :
 On clique sur « choisir l’image de test » on obtient :
On constate que l’App a arrivé de reconnaitre le chiffre 7 :
  Pourcentage de reconnaissance :
 
