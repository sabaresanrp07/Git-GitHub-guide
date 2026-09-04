###### \# Git GitHub





* Git - version controle system as software
* runs on computer local repo



* GitHub - Website/cloud service
* Stores Git repositories online





###### \# Git Terminology

###### 

###### \## 1. Git

###### 

###### \*\*Git\*\* — A distributed version control system used to track changes in files and manage project history.

###### 

###### \---

###### 

###### \## 2. Directory

###### 

###### \*\*Directory\*\* — Simply a folder on your computer.

###### 

###### Example:

###### 

###### ```text

###### Machine-Learning/





###### \# Create local repo and connect to GitHub repo before this create a repo in GitHub



* git init
* git add .
* git commit -m "Initial commit"
* git branch -M main
* git remote add origin https://github.com/sabaresanrp07/"REPO\_NAME".git
* git push -u origin main



###### \# remove a folder from Git/GitHub



* git rm -r --cached "FOLDER\_NAME"
* git commit -m "Remove folder from repository"
* git push



###### \# when u have deleted GitHub repo this single cmd remove folder from git



* Remove-Item -Recurse -Force .git



###### \# GitHub to ignore the unwanted file 



* New-Item .gitignore
* code .gitignore (after this a file opens where u write files that are unwanted like below)



\# Python cache

\_\_pycache\_\_/

\*.pyc



\# Jupyter

.ipynb\_checkpoints/



\# VS Code

.vscode/



\# Temporary files

\*.tmp

\*.temp

\*.bak

\*.swp

\*\~



* git add .gitignore
* git commit -m "Add gitignore"
* git push









