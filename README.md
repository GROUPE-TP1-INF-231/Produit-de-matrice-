Produit de matrices en C

Description du programme 

Ce programme permet de calculer le produit de deux matrices en langage C.
Pour rappel, la multiplication de matrices est possible uniquement si le nombre de colonnes de la première matrice (A) est égal au nombre de lignes de la seconde matrice (B), c’est-à-dire si a1 == b2.
Le résultat est une nouvelle matrice C de taille (a1 × b2).

L’idée principale est d’utiliser trois boucles imbriquées :

la première parcourt les lignes de A,

la deuxième parcourt les colonnes de B,

la troisième sert à calculer la somme des produits correspondants.

---------------------------------------------------

Compilation

Pour compiler le code, utilisez la commande :

gcc produit_matrices.c -o produit_matrices

----------------------------------------------------
Exécution

Une fois compilé, on lance le programme comme suit :

./produit_matrices


Exemple d’utilisation

Entrées données par l’utilisateur :

Entrez dimensions de A (lignes colonnes): 2 3
Entrez dimensions de B (lignes colonnes): 3 2
Entrez les éléments de A:
1 2 3
4 5 6
Entrez les éléments de B:
7 8
9 10
11 12

Résultat affiché :

Produit A x B:
58 64
139 154

