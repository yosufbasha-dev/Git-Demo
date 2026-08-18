# Learning git & github
<!-- basic commands for git -->

<!-- initial commands git -->
git config --global user.name yosuf
git config --global user.email yosufbasha.n.912@gmail.com

<!-- basic commands -->
git status
ls
git log
mkdir filename
cd filename


<!-- Flow from cloning to push into github -->
git clone
git status
git add .
git commit -m
git push -u origin main
git push origin main

<!-- Flow from creating project to pushing into github  -->
git init 
git remote add origin <link> <!-- creating a repo first in github -->
git add .
git commit -m 
git push origin main

<!-- branch commands -->
git branch
git branch -M feature 1
git checkout brnchName
git checkout -b New branch
git checkout -d delete branch

<!-- reset -->
git reset
git reset hashcode
git reset head~1 --> to back from 1 commit

<!-- to downlode letest changes from github -->
git pull origin main
git fetch origin main
