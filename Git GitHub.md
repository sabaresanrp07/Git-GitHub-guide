## Git GitHub

- Git - version controle system as software
- runs on computer local repo

- GitHub - Website/cloud service
- Stores Git repositories online

## Create local repo and connect to GitHub repo before this create a repo in GitHub

- git init
- git add .
- git commit -m "Initial commit"
- git branch -M main
- git remote add origin https://github.com/sabaresanrp07/"REPO\_NAME".git
- git push -u origin main

## remove a folder from Git/GitHub

- git rm -r --cached "FOLDER\_NAME"
- git commit -m "Remove folder from repository"
- git push

## when u have deleted GitHub repo this single cmd remove folder from git

- Remove-Item -Recurse -Force .git

## GitHub to ignore the unwanted file 

- New-Item .gitignore
- code .gitignore (after this a file opens where u write files extension of file to ignore)
- git add .gitignore
- git commit -m "Add gitignore"
- git push









