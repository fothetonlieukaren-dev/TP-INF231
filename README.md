Exercice 1 : Somme de matrices
But : Calculer la somme de deux matrices de même dimension.
Principe : on additionne chaque élément correspondant : C[i][j] = A[i][j] + B[i][j].
Entrées : dimensions de la matrice (m, n), puis les éléments des matrices A et B.
Sortie : la matrice somme C.


Exercice 2 : Produit de matrices
But : Calculer le produit matriciel C = A × B.
Principe : C[i][j] = somme( A[i][k] * B[k][j] ) pour k=0..n-1.
Entrées : dimensions m, n, p et les matrices A (m×n) et B (n×p).
Sortie : matrice C (m×p).


Exercice 3 : Recherche séquentielle
But : Chercher si un élément existe dans un tableau.
Principe : parcourir le tableau élément par élément jusqu’à trouver la valeur.
Variable clé : trouver (booléenne → vrai/faux).
Entrées : taille du tableau, éléments du tableau, valeur recherchée.
Sortie : message indiquant si l’élément est trouvé (et sa position).


Exercice 4 : Produit a × b sans *
But : Calculer le produit de deux entiers positifs sans utiliser l’opérateur *.
Principe : répéter des additions successives en utilisant uniquement +1.
Boucle imbriquée : pour chaque répétition de b, on ajoute a au résultat avec +1.
Entrées : deux entiers a et b.
Sortie : produit a × b.


Exercice 5 : Tester si un tableau est trié
But : Vérifier si les éléments d’un tableau sont triés en ordre croissant.
Principe : comparer chaque élément avec le suivant.
Condition : si un T[i] > T[i+1], le tableau n’est pas trié.
Entrées : taille du tableau, éléments.
Sortie : message 'trie' ou 'non trie'.


Exercice 6 : Médiane d’un tableau
But : Trouver la médiane d’un tableau.
Principe :
- Trier le tableau.
- Si n impair → médiane = élément du milieu.
- Si n pair → médiane = moyenne des deux éléments du milieu.


  Exercice 7 inversion tableau

  But : Inverser l’ordre des éléments dans un tableau.
Principe : échanger le premier avec le dernier, le deuxième avec l’avant-dernier, etc.
Entrées : taille du tableau, éléments.
Sortie : tableau inversé.
Exercice 8 : Produit vectoriel (3D)
But : Calculer le produit vectoriel de deux vecteurs en 3 dimensions.
Formule :
Cx = Ay*Bz - Az*By
Cy = Az*Bx - Ax*Bz
Cz = Ax*By - Ay*Bx
Entrées : deux vecteurs A et B (3 composantes chacun).
Sortie : vecteur résultat C (3 composantes).
Exercice 9 : Produit vecteur × matrice
But : Calculer le produit d’un vecteur ligne (1×n) par une matrice (n×m).
Principe : R[j] = somme( V[i] × M[i][j] ) pour i=0..n-1.
Entrées : dimensions n, m ; vecteur V (taille n), matrice M (n×m).
Sortie : vecteur résultat R (taille m).
