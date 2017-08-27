# GIT Common Command

+ Set user and email
  + `git config --global user.name="<name>"`
  + `git config --global user.email=<email>`

+ Set SSH
  + `ssh-keygen -t rsa -C "<email>"`
  + Copy the file content `id_rsa.pub` to GitHub.com on your account.
  + Test: `ssh git@github.com`

+ Create a local repository
  + `git init [<dir>]`

+ Add files
  + `git add <file or dir>`
  + Example: `git add *`

+ Delete files
  + `git rm <file>`
  + `git rm -rf <dir>`

+ Commit
  + `git commit [-m "<commit message>"]`

+ List branches
  + `git branch`

+ Create a new branch
  + `git branch <name>`

+ Delete a branch
  + `git branch -d <branch name>`

+ Switch to a branch
  + `git checkout <branch name>`

+ Add a tag to a branch
  + `git tag -a <name>`

+ Combine local to remote(GitHub)
  + `git remote add <alias> <address>`
  + `git remote add origin <GitHub address>`

+ Push a branch
  + `git push -u <alias> <branch name>`
  + `git push -u <alias> <local branch name>:<remote branch name>`
  + `git push -u origin <branch name>`
  + `git push -u origin <local branch name>:<remote branch name>`

+ Delete remote branch
  + `git push -u <alias> :<remote branch name>`
  + `git push -u <alias> --delete <remote branch name>`
  + `git push -u origin :<remote branch name>`
  + `git push -u origin --delete <remote branch name>`

+ Download a new repository frome GitHub
  + `git clone <address>`

+ Delete remote alias
  + `git remote rm <alias>`

+ To be continued...