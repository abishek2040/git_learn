Hello there, let's get started with Git. 

* Here, we'll go through the basics of git. 

* From adding code,  making changes committing the code to pushing the code and fetching it to and 
from the remote repository. 

Branching: 

    1. One of the main aspect of git is branches. Here, we'll see how to create branches in git and 
    how to switch between and compare different branches. 

    2. The act of switching between branches is called checkout. 

    3. we use the git branch command to list out the branches, the local branches only. 

    4. Here, we create a new branch, using the following command: git checkout -b New_branch:
    The -b creates the branch "New_branch" and checks it out - meaning switches to the New_branch. 


Git Commands: Here's a list of most frequently git commands. 

    i. git clone "remote_repo link" - Clones a remote repository into the current directory 

    ii. git checkout __branchname__ - Let's you checkout an existing branch

    iii. git checkout -b branchname : Creates and checksout the branch

    iv. git branch : Lists out all the branches

    v. git add . : Adds all the files to the git index 

    vi. git add filename1 filename2 : Adds multiple files to your index

    vii. git  commit -m "Message goes here"

    viii. git pull origins branchname: Pulls the latest changes from the remote branch

    ix. git push origin branchname: Pushes branchname to the remote

    x. git stash stashes your work away from your working environment. 

    xii. git stash pop takes the added stash and adds into the working environment

    xiii. git stash pop stashId takes a specific stash and adds it to your working environment

    xiv. git stash list shows all your stashes

    xv. git remote set-url origin https://gitgub.com/ USERNAME/REPOSITORY.git changes the remote URL of your Git system.

    