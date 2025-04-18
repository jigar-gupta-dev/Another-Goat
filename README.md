> Git init 
- It initializes the pwd / repository 
- It creates a hidden folder .git which contains all the changes made in repository 

> Git status 
- It shows the status of the repository 

> Git add .
- It adds the changes to the staging area or phase 

> Git commit -m "message"
- It commits the changes from staging area to the repository 
- -m is used to add the message to the commit, it is flag

> Git log 
- It shows the log of the repository

> git branch -M main 
- It renames the branch to main forecefully even if it is named already 

> git remote add origin "url"
- It adds the remote repository to the local repository as origin

> git push -u origin main
- It pushes the changes from local repository to remote repository

> git push
- It pushes the changes from local repository to remote repository

> To use SSH instead of HTTPS
- git remote -v
- ls ~/.ssh  
- ssh-keygen -t ed25519 -C "your-github-email"
- hit enter and enter again
- cat ~/.ssh/id_ed25519.pub 
- copy the output 
- Go to GitHub → Settings → SSH and GPG keys → New SSH key → Title → Paste the key → Add SSH key → Test SSH
- git remote  set-url origin et-url origin EMAIL:username/repository.git
- yes and yes again
- ssh -T git@github.com
- yes and yes again
- Good to go 

> git diff --staged
- It shows the difference between the changes made in the staging area and the repository

> git diff
- It shows the difference between the changes made in the repository

> git branch 
- It shows the branches in the repository

> git checkout -b branch-name
- It creates a new branch and switches to it

> git checkout branch-name
- It switches to the branch

> git merge branch-name
- It merges the branch to the current branch

> git branch -d branch-name
- It deletes the branch

> git branch -D branch-name
- It deletes the branch forcefully

> git reset 
- It resets the changes made in the repository

> git reset --hard commit-id
- It resets the changes made in the repository to the commit-id

> git reset --soft commit-id
- It resets the changes made in the repository to the commit-id but it keeps the changes in the staging area

> git reset --soft <commit-id>
- It resets the changes made in the repository to the commit-id but it keeps the changes in the staging area

> git reset --hard <commit-id>
- It resets the changes made in the repository to the commit-id and it deletes the changes in the staging area

> git stash
- It stashes the changes made in the repository

> git stash apply
- It applies the changes made in the repository

> git stash list
- It shows the list of stashes

> git stash drop stash@{0}
- It drops the stash

> git tag tag-name
- It creates a tag

> git tag -a tag-name -m "message"
- It creates a tag with a message

> git tag -d tag-name
- It deletes the tag

> git tag -a tag-name -m "message"
- It creates a tag with a message

> git rm file-name
- It removes the file from the repository

> git clean -fd
- It removes the untracked files from the repository
- f forces the removal 
- d removes untracked directories as well 

> git fetch origin
- It fetches the changes from the remote repository
