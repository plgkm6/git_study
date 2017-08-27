# GIT Common Commands

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

+ Merge branch from remote (to local)
  + `git pull <alias> <remote branch name>:<local branch name>`
  + `git pull origin <remote branch name>:<local branch name>`
  + `git pull <alias> <branch name>`
  + `git pull origin <branch name>`

+ Safety merge branch from remote (to local), example1
  + `git fetch origin <remote branch name>`
  + `git log -p <local branch name>..origin/<remote branch name>`
  + `git merge origin/<remote branch name>`

+ Safety merge branch from remote (to local), example2
  + `git fetch origin <remote branch name>:<to local temp branch name>`
  + `git deff <local temp branch name>`
  + `git merge <local temp branch name>`

+ To be continued...


>Hello  
> Welcome to contact me to add more Git commands.  
> My Email: `plgkm6@hotmail.com` or `plgkm6@gmail.com`,  
> you can also contact me by `463990503@qq.com`.  
> Apparently, my QQ number is `463990503`.