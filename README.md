# Check_Algo3
Le probleme:

Le tri par insertion est un algorithme de tri simple qui fonctionne de la même manière que nous trions les cartes à jouer entre nos mains. 
Chaque fois que nous prenons une nouvelle carte, nous la plaçons au bon endroit dans notre main.
Instructions

Chaque fois, travaillez uniquement avec le premier élément i-1 du tableau
Choisissez l'élément arr[i] et insérez-le dans une séquence triée dans le tableau de 0 à i-1.
La solution:

-On commence par déclarer les varibles: Tableau Tab, i et j pour les boucles
et k qui va contenir l'entier courant pour faire les permutation.
-La boucle FOR qui va parcourir le tableau élément par élément
  *on va mémoriser l'entier courant dans k et son indice dans j
  *la boucle wHile a deux condition j positif, comme om va le décrementer on ne va pas
  déborder,et la condition de trouver un element supeieur a l'element en cour
  * dans ce cas on ecrase l'element en cours sans le perdre parceque on l'a memorise dansk
  et on decremente j pour la prochaine itteration
  *A la sortie du While on recupere l'entier " ecrasé" qui n'etait pas a sa place
  *on avance pour traiter l'entier prochain de la meme façon
  conclusion : chaque entier va etre comparer a ses précédéceur et inserer a sa bonne place
  parmi les élements deja triés
