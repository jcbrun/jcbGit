l'objectif de ce document est de résumer les actions qui ont été menées pour ce projet
de formation git.

sur mon poste local :
- création d'un répertoire pour mon projet : mkdir jcbGit
- positionement dans ce répertoire 
- création d'un fichier README.txt
- création d'un repo git : git init
- consultation de le log git : git log
- consultation du status des fichiers pris ou pas en compte dans le repo : git status

- création d'un script lsgit.sh qui permet de lister les fichiers et le status du repo sur ces fichiers
- création d'un fichier test01.txt : touch test01.txt


###### premier commit de l'ensemble des fichiers du repertoire de travail
- pour cela il faut ajouter les fichiers qu'on veut suivre au repo
git add README.txt
git add test01.txt
git add lsgit.sh
- les fichiers sont maintenant suivis
- nous faisons notre premier commit : git commit -m "Version initiale avec les 3 fichiers README.txt, test01.txt, lsgit.sh"

###### Création d'un repo sur github
- création d'un repo sur github : jcbGit
git remote add origin https://github.com/jcbrun/jcbGit.git
- push de la version innitiale
git push -u origin master

###### version 1 : mise à jour et création de nouveau fichier
- modif README.txt
- création modif_entre_init_v1.txt
- integration des données dans la version
git add modif_entre_init_v1.txt
git add README.txt
- commit des modifs
git commit -m "Version 1 : modif README.txt et création modif_entre_init_v1.txt"
git push -u origin master

###### version 2 : mise à jour et création de nouveau fichier
- modif README.txt
- création modif_entre_v1_v2.txt
- integration des données dans la version
git add modif_entre_v1_v2.txt
git add README.txt
- commit des modifs
git commit -m "Version 1 : modif README.txt et création modif_entre_v1_v2.txt"
git push -u origin master


