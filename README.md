# Git Commands
==============

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
| `git commit -m "[commit message]"` | Commit changes |
| `git branch -M main` | branch name set master to main |
| `git remote add origin [url]` | connect to remote reposatory |
| `git push -u origin main` | push code to remote repoosatory |

## resolve problem
| problem | solution |
| ------- | -------- |
| git push origin main 
 remote: Permission to [url] 
 fatal: unable to access [url] | Control Panel -> Credential Manager -> 
                                Windows Credentials -> 
                                remove github username and password |

| failed to push some refs to | `git push -u origin main -f` | 