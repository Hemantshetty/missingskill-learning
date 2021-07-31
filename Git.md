# Git
1. Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
2. Git is easy to learn and has a tiny footprint with lightning fast performance 
3. How to install git using terminal:
> _COMMAND FOR GIT INSTALLATION IN YOUR NIX TERMINAL_  
>         **sudo apt install git**
### GIT COMMANDS

![gitcommand01](https://user-images.githubusercontent.com/81672261/127742216-2b1ba765-e2c9-40ed-882b-476ada1da70b.PNG)
![gitcommand02](https://user-images.githubusercontent.com/81672261/127742220-dfc4b166-1fde-4d28-9e7e-f6606d8781cd.PNG)


| **COMMAND** |  **DESCRIPTION**|
|----------|-----------|
|git config --global user.email <"email_address">| configure user email --global(to all repositary) if not given then setting will be for current repository| 
|git config --global user.name <"user_name">|configure user name.|
| git init . | turn current directory into empty repository.|
|git add \<file_name/Dir_name> | add a file/dir to staging area/be tracked.|
|git add . | add all files that are not staged.|
|git commit -m \<message_for_commit> | record changes of file to local repository|
|git commit -a -m \<message_for_commit> | commit all the staged changes.| 
|git status | return current state of working tree.|
|git push \<remote_name> \<branch_name> | send local commits to remote repository.|
|git log | commit history of repository.|
|git remote add \<remote_name> \<remote_repo_URL> | add remote repositories.|
|git clone \<remote_repo_URL> | to create local working copy of existing remote repository.|
|git pull \<remote_name> \<branch_name> | to get latest version of remote repository of specified branch. If many people make changes the our push may get rejected the use this command|
|git branch <branch_name> | create new branch|
|git branch -D <branch_name> | delete a branch|
|git checkout <branch_name> | switch to specified branch.|
|git checkout -b <new_branch_name> | checkout to and create specified branch.|
|git switch <branch_name> | switch to specified branch.|
|git merge <branch_name> | merge changes from specified branch into current branch.|
|git show [commit_SHA] | metadata and content changes of specified commit.|
|git stash | to save work without commit|
|git stash pop | to pop the save work that was not committed|
|git reset <commit_id> --soft | git reset is used to move current head to commit specified,this command takes head back to stagging area |
|git reset <commit_id> --mix | takes head back to working area|
|git reset <commit_id> --hard |permanent remove from working area, changes made after this commit will be gon from working area |

