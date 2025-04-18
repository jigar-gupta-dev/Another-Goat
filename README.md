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


