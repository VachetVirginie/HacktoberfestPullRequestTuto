Description étape par étape de la création d'une pull request pour les débutants. 

OS: Linux

Etapes:

1.Forkez le repo afin que vous puissiez travailler sur le repo localement.

2.Creez upstream

		git remote add upstream <clone_link>

3.Ouvrez le terminal (ctrl + alt + t) et exécutez les commandes ci-dessous

		git status 
		git add . 
		git commit -m "commit_message"
    
4.Exécutez les étapes ci-dessous pour synchroniser votre branche avec la branche principale.


		git fetch upstream
		git merge upstream/master
    
5.Pour commiter:

		git push origin master
    
6.S'il reste quelque chose sur le stack et que vous n'en voulez pas

		git stash
    

Remarque: l'étape 4 n'est pas requise si vous êtes sûr que le dernier commit est le vôtre.
