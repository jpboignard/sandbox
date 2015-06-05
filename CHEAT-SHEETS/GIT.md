<<<<<<< HEAD
Commandes basiques
==================

    git config --global user.name "myusername"
    git config --global user.email "email@gmail.com"

Initialiser un dépot local, et le connecter avec un dépôt distant sur github

    mkdir myproject;cd myproject
    git init
    git remote add origin https://github.com/projet/projet.git

Faire des modifications et les commiter

    git add filename
    git commit -m "my good comment"

Pousser les modifs sur le dépôt ( '-u' pour n'avoir à faire que 'git push' par la suite)

    git push -u origin master

Récupérer les modifs:

    git pull orgin master

Voir les différences:

    git diff HEAD

Ajouter des fichiers dans la zone de commit

    git add octofamily/octodog.txt

Voir les changements que nous venons de faire

    git diff --staged

Pour annuler la modif sur un fichier:

    git reset octofamily/octodog.txt

Pour annuler les modifs jusqu'au dernier commit d'octocat.txt

    git checkout -- octocat.txt

Pour effectuer des modifications dans une branche:
=======
git config --global user.name "myusername"

git config --global user.email "email@gmail.com"

mkdir myproject;cd myproject

    git init

    git remote add origin https://github.com/projet/projet.git

    git add filename

    git commit -m "my good comment"

Pousser les modifs sur le dépôt:
    git push -u origin master
-u pour que git se rappelle, et n'avoir à faire que git "push"

Récupérer les modifs:
    git pull orgin master

Voir les différences:
    git diff HEAD

    git add octofamily/octodog.txt

Voir les changements que nous venons de faire
    git diff --staged

Pour annuler la modif sur un fichier
    git reset octofamily/octodog.txt

Ppour annuler les modifs jusqu'au dernier commit d'octocat.txt
    git checkout -- octocat.txt

>>>>>>> 0e6fcc8... First step

    git branch aspecialwork
    git checkout aspecialwork

<<<<<<< HEAD
Supprimer certains fichiers dans la branche:

    git rm "*.txt"
    git commit -m " Suppression fichiers"

Revenir dans la branche master pour récupérer les modifs de la branche dans master

    git checkout master
    git merge aspecialwork

Supprimer la branche:

    git branch -d aspecialwork

Pousser tout sur le serveur:

=======
Supprimer certains fichiers dans la branche
    git rm "*.txt"
    git commit -m " Suppression fichiers"

Revenir dans la branche master
    git checkout master

    git merge aspecialwork
Suppression de la branche:
    git branch -d aspecialwork
Pour pousser tout sur le serveur:
>>>>>>> 0e6fcc8... First step
    git push
