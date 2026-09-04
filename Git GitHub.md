## Git GitHub

- Git - version controle system as software
- runs on computer local repo

- GitHub - Website/cloud service
- Stores Git repositories online

# I will tell u how all works first create a Repository in GitHub then go to terminal I prefer VS Code terminal after that use the below cmds to connect ur local folder to Git and GitHub


# 1

## Create local repo and connect to GitHub repo before this create a repo in GitHub

- echo "# Git-GitHub-guide" >> README.md

### this cmd creates local Repo(this is local repo .git/ mostly this is hidden) inside ur folder 
- git init 

- git add .
- git commit -m "Initial commit"
- git branch -M main

### this cmd connects that local Git repository to the GitHub repository
- git remote add origin https://github.com/"your_username"/"REPO_NAME".git


- git push -u origin main

# Every time u work on ur working tree (directory where u edit do changes) do this 

- git add .(. means add everything when u have worked on may file in your folder use add . or u can also add specific file like git add .num.py)

- git commit -m "changes had done"
- git push 

# These are some extra cmd 

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

