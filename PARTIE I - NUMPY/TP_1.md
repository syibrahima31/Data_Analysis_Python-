# TP 1: NUMPY DATA STRUCTURE
---------------------------------------------------

## Probléme 1 
---------------------------
Considérons le vecteur suivant :   $$x=[1,2,3,4,5]$$

 

1. Créer ce vecteur à l’aide d’un tableau que l’on appellera `x`.

2. Afficher le type de `x` puis sa longueur.

3. Extraire le premier élément, puis en faire de même avec le dernier.

3. Extraire les trois premiers éléments et les stocker dans un vecteur que l’on nommera `a`.

4. Extraire les 1er, 2e et 5e éléments du vecteur (attention aux positions) ; les stocker dans un vecteur que l’on nommera `b`.
5. Additionner le nombre `10` au vecteur `x`, puis multiplier le résultat par `2`.

5. Effectuer l’addition de `a` et `b`, commenter le résultat.

6. Effectuer l’addition suivante : `x+a` ; commenter le résultat, puis regarder le résultat de `a+x`.

7. Multiplier le vecteur par le scalaire `c` que l’on fixera à `2`.

8. Effectuer la multiplication de `a` et `b` ; commenter le résultat.

9. Effectier la multiplication suivante : `x*a` ; commenter le résultats.

10. Récupérer les positions des multiples de `2` et les stocker dans un vecteur que l’on nommera `ind`, piuis conserver uniquement les multiples de `2` de `x` dans un vecteur que l’on nommera `mult_2`.

11. Afficher les éléments de `x` qui sont multiples de `3` et multiples de `2`.
12. Afficher les éléments de `x` qui sont multiples de `3` ou multiples de `2`.
13. Calculer la somme des éléments de `x`.
14. Remplacer le premier élément de `x` par un `4`.
15. Remplacer le premier élément de `x` par la valeur `NaN`, puis calculer la somme des éléments de `x`.
18. Supprimer le vecteur `x`

------------------------------------------------------------------------------------------------------------------------------------


Probléme 2:
---------------


Créer la  matrice  : 
$$A=\begin{pmatrix}-3&5&6 \\-1&2&2 \\ 1& -1& -1 \end{pmatrix}$$


1.  Afficher la dimension de  `A`, son nombre de colonnes, son nombre de lignes et sa longueur.
2.  Extraire la seconde colonne de  `A`, puis la première ligne. 4.Extraire l’élément en troisième position à la première ligne.
3.  Extraire la sous-matrice de dimension  $2\times 2$  du coin inférieur de  `A`, c’est-à-dire:
$$A=\begin{pmatrix}2&2 \\-1&-1 \end{pmatrix}$$
4.  Calculer la somme des colonnes puis des lignes de `A`.
5.  Afficher la diagonale de  `A`.
6. Rajouter le vecteur $\begin{pmatrix}1 &2 & 3\end{pmatrix}^T$   
à droite de la matrice `A` et stocker le résultat dans un objet appelé `B`.

7.  Retirer le quatrième vecteur de  `B`.
8.  Retirer la première et la troisième ligne de  `B`.
9.  Ajouter le scalaire `10`  à  `A`.
10.  Ajouter le vecteur $\begin{pmatrix}1 &2 & 3\end{pmatrix}^T$     
11.  Ajouter la matrice identité  $I_{3}$  à  `A`.
12.   Diviser tous les éléments de la matrice  `A`  par `2`.

13. Multiplier la matrice `A` par le vecteur $\begin{pmatrix}1 &2 & 3\end{pmatrix}^T$ 
14.   Afficher la transposée de  `A`.
15. 1.  Effectuer le produit avec transposition $A^{T}A$
