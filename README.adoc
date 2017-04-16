.Informations générales
[format="csv"]
|======================
Rédacteur, K3rn€l P4n1k
Date, 01/01/1970
État, En développement
|======================

# Collatz

.Objectif du document
Documente l'usage du script `collatz`

.Description générale
Ce script à pour but d'implémenter le comportement suivant.

. Prend un nombre
. Tant que ce nombre n'a pas déjà rencontré
.. Si ce nombre est pair alors on le divise par 2
.. Si ce nombre est impair alors on le multiplie par 3 puis on lui ajoute 1
.. Fin tant que

.Intention
Ce script à été implémanté pour voir ce qui se passe lorsqu'on le nourrit avec des nombres premiers.

# Usage

.Signature
[source, bash]
----
collatz <nombre>
----

.Arguments
[format="csv"]
|====
*nombre*, Nombre dont on veut connaître l'évolution
|====

.Exemple avec le nombre 7
[source, bash]
----
collatz 7
----

.Résultat
----
7;22;11;34;17;52;26;13;40;20;10;5;16;8;4;2;1
----

# Commentaires
Aucun

# Références
[format="csv"]
|====
Numberphile, https://www.youtube.com/watch?v=5mFpVDpKX70
njwildberger, https://www.youtube.com/watch?v=K0yMyUn--0s
|====
