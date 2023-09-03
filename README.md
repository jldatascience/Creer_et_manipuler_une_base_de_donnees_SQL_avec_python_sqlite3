# 📈 Créer et manipuler une base de données SQL avec python sqlite3



## Contexte

Le code utilise le module python sqlite3 pour se connecter à la base de données, exécuter des instructions SQL et gérer les transactions.

SQLite est un moteur de base de données relationnelle léger, autonome et open source qui permet de stocker et d'extraire des données de manière simple et efficace. Il est souvent utilisé dans les appareils mobiles, les systèmes embarqués et les environnements en demande.

SQLite ne nécessite pas de configuration ni de serveur dédié, ce qui en fait un choix populaire pour les applications qui n'ont pas besoin de fonctionnalités complexes de gestion de base de données. Il peut être intégré directement dans une application sans nécessiter l'installation d'un logiciel distinct.

SQLite supporte le standard SQL, ce qui signifie que les développeurs peuvent utiliser des instructions SQL courantes pour interagir avec les données de la base de données. En outre, SQLite est conforme à la norme ACID (Atomicité, Consistance, Isolation, Durabilité), garantissant ainsi l'intégrité et la fiabilité des données.




## Architecture de SQLite : Base de données orientée en ligne

Les lignes d'une table sont sauvegardées de manière contiguë en mémoire.
Cela permet d'insérer ou de supprimer facilement des enregistrements.
Revers de la médaille, il est plus coûteux de faire du calcul sur une colonne entière, car cela nécessite de parcourir l'ensemble des lignes. Ces bases de données sont optimisées pour le transactionnel et sont utilisées pour des système OLTP (OnLine Transactional Processing), par exemple une base de données de production gérant des utilisateurs.



## Ensemble de données

Je crée directement la base de données SQLite dans le notebook ci-joint.



## Démarche

Cf. le notebook ci-joint.




## Conclusion

Ce use case montre comment :

1.	créer une base de données SQLite,
2.	insérer des données,
3.  supprimer des données,
4.	effectuer une requête et extraire des données.






