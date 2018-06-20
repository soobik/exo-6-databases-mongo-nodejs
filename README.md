# exo-6-databases-mongo-nodejs

Exo-6-databases-mongo-nodejs Utilisation d'une base de données mongodb avec nodejs


# Objectif : 

:one: => __Afficher__ sur une page HTML une information enregistrée dans la base de donnée via node js.

:two: => Ajouter un formulaire à la page permettant l'__insertion__ des données dans la base de données.

:three: => Creer une page HTML avec un formulaire permetant l'__édition__ d'une entrée de la base de donnée. 
           L'id de l'entrée à éditer doit etre passé dans l'URL et récupéré via une route sous la forme suivante :
           
           __ /personne/1 __
           
:four: => :bomb:
           


# Création de votre base :

1 - Ouvrir un terminal et ecrire mongo puis valider avec la touche entrée.

2 - use [votre prenom sans les crochets].

3 - db.personnages.insert( { name: "[votre prenom sans les crochets]", genre: "[m ou f sans les crochets]" } );

4 - db.personnages.find()

Si les inforations s'affichent vous pouvez commencer a coder votre application.

# Infos : 

URI de connexion a votre base : mongodb://localhost:27017/[votre prenom sans les crochets].


