# Learning git & github
## basic commands for git  

### initial commands git
git config --global user.name yosuf <br>
git config --global user.email yosufbasha.n.912@gmail.com  <br>

### basic commands 
git status  <br>
ls   <br>
git log  <br>
mkdir filename  <br>
cd filename  <br>


### Flow from cloning to push into github 
git clone  <br>
git status  <br>
git add .  <br>
git commit -m  <br>
git push -u origin main  <br>
git push origin main  <br>

### Flow from creating project to pushing into github
git init  <br>
git remote add origin <link> creating a repo first in github  <br>
git add .  <br>
git commit -m  <br>
git push origin main  <br>

### branch commands
git branch  <br>
git branch -M feature 1  <br>
git checkout brnchName  <br>
git checkout -b New branch  <br>
git checkout -d delete branch  <br>

### reset
git reset  <br>
git reset hashcode <br>
git reset head~1 --> to back from 1 commit  <br>

### to downlode letest changes from github
git pull origin main  <br>
git fetch origin main  <br>
