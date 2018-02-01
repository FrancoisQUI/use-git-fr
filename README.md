<p align="center">
	<img align="center" alt="Git" src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" width="150"/>
	<img align="center" alt="Github" src="https://assets-cdn.github.com/images/modules/logos_page/Octocat.png" width="150"/><br>   	   <strong>Git & Github</strong>
	<hr />
</p>

## Etape 1: Installer git

* #### Pour Windows :

Rendez vous sur http://msysgit.github.io et téléchargez la dernière version disponible.

* #### Pour Mac :

Téléchargez la dernière version de Git sur : http://git-scm.com/downloads
Ouvrez le fichier ainsi téléchargé et suivez les instructions en laissant toutes les valeurs par défaut.

* #### Pour Linux :

Rendez-vous dans le terminal, et installez git de cette manière :`sudo apt-get install git`


## Etape 2: Créer ou fork un repository
> Pour cette étape vous devez avoir créé un compte Github

* #### Créer un repository

Rendez-vous sur votre profil github, puis 'Repository' et cliquez sur 'New'. Définissez les champs en fonction de vos envies.
Puis cliquez sur 'Create Repository'.

* #### Fork un repository

Si vous souhaitez travailler sur un projet qui est déja existant vous pouvez le 'fork'. Rendez-vous sur la page de ce repository,
et cliquer sur 'Fork', il apparaîtra alors dans votre liste de repository.

## Etape 3: Cloner le repository

* #### Obtenir le lien .git du repository
Rendez-vous sur le repository souhaité, cliquez sur 'Clone or download', copiez le lien et ouvrir un terminal puis rapez cette commande :
`git clone <le lien du repository>`
remplacez 'le lien du repository' par le lien copié précédemment. Vous pouvez alors commencer à coder.

## Etape 4: Mettre à jour son repository local
TOus les jours effectuez un :
`git pull` afin de mettre à jour votre repository local.

## Etape 5: Faire un commit

* #### Ajouter les fichiers modifiés
Afin d'ajouter les fichiers modifiés il est nécessaire de faire un :
`git add <le chemin de ton fichier>` remplacez 'le chemin de ton fichier' par le chemin jusqu'au fichier modifié.

* #### Effectuer un commit
Afin d'effectuer un commit il faut écrire la commande :
`git commit -m '<ton message>'`
remplacez 'ton message' par la description du commit comme 'Fix Error #536' (Regarder dans le fichier CONTRIBUTING.md si vous travaillez sur un gros projet).

## Etape 6: Faire un push

Pour envoyer les modifications au repository sur github il est nécessaire d'effectuer un push comme ceci :
`git push origin <la branche>` remplacez 'la branche' par la branche choisie (Si vous fixez une erreur ou ajoutez une fonctionnalité, il est conseillé de créer une branche spéciale à son nom tel que : le nom de l'erreur ou la version).

## Etape 7 (Si le repository vous appartient): git merge

Vous pouvez fusionnez la branche courante avec une autre branche tel que : `git merge <nom de la branche>` remplacez 'nom de la branche' par le nom de la branche avec laquelle vous voulez fusionnez la branche actuelle.

## C'est fini
Vous savez maintenant utiliser les bases de git ! Mais git est plein de petits secrets ! Alors n'hésitez pas à consulter la documentation [doc](https://git-scm.com/doc)