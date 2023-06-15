# Analyseur-lexicale-et-syntaxique-du-langage-SQL
Analyseur Lexical et Syntaxique du langage SQL avec Flex et Bison
Ce projet consiste à créer un analyseur lexical et syntaxique du langage SQL en utilisant les outils Flex et Bison. 
L'objectif est de prendre une entrée SQL et de la découper en jetons lexicaux (mots-clés, identificateurs, opérateurs, etc.) pour ensuite vérifier la syntaxe et la structure grammaticale de la requête SQL.

Configuration requise
Avant de pouvoir exécuter l'analyseur lexical et syntaxique, assurez-vous d'avoir les outils suivants installés sur votre système :

Flex : un générateur d'analyseur lexical
Bison : un générateur d'analyseur syntaxique
Compilation et exécution
Pour compiler et exécuter l'analyseur lexical et syntaxique, suivez les étapes suivantes :

Clonez le dépôt GitHub sur votre machine locale.
Ouvrez une fenêtre de terminal et accédez au répertoire du projet.
Utilisez la commande make pour compiler les fichiers Flex et Bison et générer l'exécutable.
Une fois la compilation terminée, exécutez l'analyseur en utilisant la commande ./mini.
Utilisation de l'analyseur
Une fois l'analyseur exécuté, vous pouvez saisir des requêtes SQL à analyser. 
L'analyseur découpera la requête en jetons lexicaux et vérifiera la syntaxe et la structure grammaticale de la requête.

Voici un exemple d'utilisation :
SQL:
$ ./mini
Veuillez saisir une requête SQL : SELECT * FROM users WHERE age > 18;
Analyse lexicale terminée.
Analyse syntaxique terminée.
La requête est valide.
$ ./mini
Veuillez saisir une requête SQL : SELECT * FROM users WHERE age > 18;
Analyse lexicale terminée.
Analyse syntaxique terminée.
La requête est valide.
Auteur : Mouhib MANI
Date : 10/04/2023
