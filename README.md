# Github
Github learning notes
https://www.youtube.com/watch?v=Ez8F0nW6S-w

=======================================================================
**Create Githib Account:
--Create a new reporsitory
--Make your First commit (2 stage -- ADD and then Commit)

**Setting up Git:
Windows
--Visual Studio Code
--Git Bash
OR MAC
--Mac (Terminal)

=========================================================================
Then open Git we can use basic commands:
git --version
ls -lrt
pwd - current working directory

After install and setup we need to configure Git

**Git configure:
--git config --global user.name "My Name"
git config --global user.name "ravindrakumarpatel"
--git config --global user.email "My email id"
git config --global user.email "er.patelravindra@gmail.com"
git config --list
--To check what all setup has been done using git config --list command

=========================================================================
**Clone & Status:
--Clone - Cloning a repository on our local machine
git clone <- some link ->
Example: remote to local copy need to do clone
remote - Github
local - laptop/PC

--Status - displays the state of the code
git status

There are 4 types of git status:
1 - untracked
New file that git does not yet track
2 - modified
changed
3 - staged
file is ready to be committed
4 - unmodified
unchanged


So basically change means modified and newfile means untracked
Then we need to first add (staged) status
Then we have to finally commit (unchanged) status

===============================================================================
**Add & Commit:

add - adds new or changed files in your working directory to the Git staging area
git add <-file name->
or git add .        --if multiple file needs to be added in staging area


commit - it is the record of change
git commit -m "some changes"

==============================================================
** Push command

push - to command local repo content to remote repo

git push origin main

===========================================================================
**Workflow:

Local Git

Git Repo-->clone-->changes-->add-->commit-->push

===========================================================================
**Git Branch: Branch commands:

git branch - to check branch
git branch -M main - to rename branch (where main is a new name in syntax)
git checkout <-branch name-> - to navigate
git checkout -b <-new branch name-> - to create new branch
git branch -d <-branch name-> - to delete branch

============================================================================
**Merging code:

Way1
git diff <-branch name-> - to compare commits, branches, files and more)
git merge <-branch name-> - to merge two branches

Way2
Create a Pull request (PR) - 
It lets you tell others about changes you have pushed to a branch in a repository on GitHub

==============================================================================
**Pull Command:
git pull origin main
used to fetch and download content from a remote repo and immdediately update the local repo to match that content
