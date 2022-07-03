# Git Commands

### configaration & initialize

| Command | Details |
| ------- | ----------- |
| `git config --global user.name "username"` | set username |
| `git config --global user.email "email"` | set email |
| `git init` | Initialize a local Git repository |


### begin to push remote reposatory

| Command | Details |
| ------- | ----------- |
| `git add .` | add all file to staging area |
| `git commit -m "[commit message]"` | file staging area to local reposatory |
| `git branch -M main` | branch name set master to main |
| `git remote add origin [url]` | connect to remote reposatory |
| `git push -u origin main` | push code to remote repoosatory |


## resolve problem
| problem | solution |
| ------- | -------- |
| git push origin main -> remote: Permission to [url]  fatal: unable to access [url] | ControlPanel->Credential Manager ->   Windows Credentials ->  remove github username and password |
| failed to push some refs to | `git push -u origin main -f` |


## staging and unstaging
| command | Details |
| ------- | ----------- |
| `git status` | details about files situation |
| `git add [fileName]` | a specifiq file to stage area |
| `git add -a` | all file in directory and subdirectory to stage area |
| `git add .` | all file in directory without subdirectory to stage area |
| `git add *.js` | all .js file in directory without subdirectory to stage area |
| `git add **/*.js` | all .js file in directory and subdirectory to stage area |
| `git restore --staged [fileName]` | stage to unstage |
|`git diff` | What is modified |
| `git restore [fileName]` | modified to unmodified |

## commit and uncommit
| command | Details |
| ------- | ------- |
| `git commit -m "[commit message]"` | file staging area to local reposatory |
| `git log` | commit history |
| `git log --oneline` | summury commit history |
| `git show [commit-id]` | details of this commit |
| `git checkout [commit-id]` | move HEAD to specifiq commit |
| `git reset --soft HEAD^` | local repo to staging area |
| `git reset HEAD^` | local repo to unstaging area |
| `git reset --hard HEAD^` | local repo to previous commit |

## .gitignore file
| .gitignore | Details |
| ---------- | ------- |
| test.txt | ignore test.txt file |
| *.txt | ignore all .txt file |
| !main.txt | ignore .txt file without main.txt file |
| test?.txt | ignore (text1.txt/text2.txt/text3.txt...) type file |
| temp/ | ingone all in temp directory | 
