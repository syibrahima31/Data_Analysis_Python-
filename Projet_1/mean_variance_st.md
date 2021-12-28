#  Projet 1 : **Mean-Variance-Standard Deviation Calculator**

- **Prof **: Mr SY 
- **Email **: syibrahima31@gmail.com

- **Master 1 ** : DSIA, Institut supérieur Informatique 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Créez une fonction nommée `calculate()` dans un notebook  `mean_var_std.ipynb` qui utilise **Numpy** pour produire la `moyenne`, la `variance`, `l'écart-type`, le `maximum`, le `minimum` et la `somme `par  lignes, par colonnes et  pour tous les élements d'une matrice 3 x 3. 



L'entrée de la fonction doit être une liste contenant 9 chiffres. La fonction doit convertir la liste en un tableau **Numpy**  3 x 3, puis retourner un dictionnaire contenant la moyenne, la variance, l'écart-type, le maximum, le minimum et la somme le long des deux axes et pour la matrice aplatie. 

Le dictionnaire retourné doit suivre ce format:

```python
{

  'mean': [axis1, axis2, flattened],

  'variance': [axis1, axis2, flattened],

  'standard deviation': [axis1, axis2, flattened],

  'max': [axis1, axis2, flattened],

  'min': [axis1, axis2, flattened],

  'sum': [axis1, axis2, flattened]

}
```



si une liste contenant moins de 9 éléments est passée dans la fonction, celle-ci doit lever une exception `ValueError` avec le message : "La liste doit contenir neuf éléments". Les valeurs du dictionnaire retourné doivent être des listes et non des tableaux `Numpy`.

Par exemple , `calculate([0,1,2,3,4,5,6,7,8])` devrait retourner:

```python
{

  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0], 

  'variance': [[6.0, 6.0, 6.0], [0.6666666666666666, 0.6666666666666666, 0.6666666666666666], 6.666666666666667], 

  'standard deviation': [[2.449489742783178, 2.449489742783178, 2.449489742783178], [0.816496580927726, 0.816496580927726, 0.816496580927726], 2.581988897471611],

  'max': [[6, 7, 8], [2, 5, 8], 8],

  'min': [[0, 1, 2], [0, 3, 6], 0],

  'sum': [[9, 12, 15], [3, 12, 21], 36]

}
```





