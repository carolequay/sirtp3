# TP3: MongoDB

http://www.barreverte.fr/une-courte-introduction-a-redis/

## Description de MongoDB

MongoDB est un système de base de données orienté Big Data. Le point fort du Big Data est que les colonnes ne sont pas fixes comme dans les bases de données non orienté Big Data, comme par exemple celles en PostgreSQL.

## Questions

* Quelles sont les limites d'une base de données orientée document?
	* On ne peut pas faire de jointures (ou on peut seulement difficilement en faire)
	* Ce n'est pas performant pour faire des traitements comparant toutes les entrées de la base, car il faudra lire les documents un à un

* Quels sont les types de données stockés dans Redis?
Types de données manipulées : à la base, une chaîne binary-safe dans laquelle on peut donc stocker et manipuler des valeurs numériques et binaires. À partir de ce type de donnée de base, Redis offre des listes, des ensembles, des ensembles triés et des tables de hachage. Ces structures permettent de gérer beaucoup de besoins de manipulations de données, et ces structures sont optimisées en mémoire.
* Seulement des données simples
	* Chaînes de caractères
	* Tableaux associatifs
	* Listes
	* Ensembles de données
	* Bitmaps
	* Hyperlog
	* Indexes géospatiaux

* Que peut-on faire comme types de requêtes?
```Il est impossible de requêter les valeurs comme on le fait habituellement avec un WHERE en MySQL```
* Les requêtes radius (pour le géospatial)
* Les range queries (pour les ensembles)
