#Git Quest
	

##Ajout de ressource Git

https://help.github.com/articles/changing-a-remote-s-url/

## Créer un README et un commit

	Nous devons dans un premier temps créer un nouveau repository sur Github afin d'orienter Git pour ensuite mettre dans le dossier le README.

	Une fois crée, nous devons cloner le repository afin de pouvoir y enregistrer le README en utilisant la commande : git clone "url-du-repository"

	Maintenant nous créeons le README avec la commande touch ou vim (suivi du nom et de l'extension).

	Il faut ensuite l'ajouter au repository, il faut donc entrer la commande: git add nom_du_fichier

	Il s'agit ensuite de vérifier que le fichier est en raccord avec la branch avec la commande : git status

	Dans tout les cas de modifications du fichier, nous devons ajouter un annotation au fichier afin d'expliquer la dite modification.

	Il faut donc entrer la ligne de commande : git commit -m "Objet de l'annotation en rapport avec le commit"

	En ensuite finalement l'envoyer sur Github et sa branche correspondante avec la commande : git push -u origin master	

