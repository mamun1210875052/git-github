# Git Commands

### configaration & initialize

| Command | Description |
| ------- | ----------- |
| `git config --global user.name "username"` | set username |
| `git config --global user.email "email"` | set email |
| `git init` | Initialize a local Git repository |


### begin to push remote reposatory

| Command | Description |
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
| command | Description |
| `git status` | details about files situation |
| `git add -a` | all file in directory and subdirectory to stage area |
| `git add .` | all file in directory without subdirectory to stage area |
| `git add *.js` | all .js file in directory without subdirectory to stage area |
| `git add **/*.js` | all .js file in directory and subdirectory to stage area |

