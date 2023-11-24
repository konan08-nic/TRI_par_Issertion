# TRI_par_Issertion
pour ce problème, je vais écrire unre procedure que je vais nommé tri_insertion

je vais declaré mes différents variable que je vais initialisé

ensuite je demande à l'utilisateur de saisir la taille du tableau et de remplir le tableau.

je vais affecté à la variable cle la valeur Tab[i]. C’est elle que l’on va insérer.

On affecte à j la valeur de i pour commencer le parcours des éléments précédents.

Tant que j est positif et que Tab[j-1] est strictement supérieur à cle (= Tab[i]),
on décale Tab[j] au rang j-1.

	On décale j au rang j−1 pour s’intéresser à l’élément précédent.
Fin de la boucle « Tant que ». On a décalé tous les éléments du tableau pour insérer cle = Tab[i].

On insère cle = Tab[i] à sa place (en sortie de boucle, sa place est j-1).
FinPour	Fin de la boucle « Pour ».
