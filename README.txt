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


