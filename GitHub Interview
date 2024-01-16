                                              ***GIT***

1. Version Control:
version control is a system that records/manages changes to documents, computer programs etc. over time. It helps us track changes when multiple people work on the same project.


ADVANTAGES:
Versioning is automatic. Team collaboration is simple. easy access to previous versions. Only modified code is stored across different versions hence saves storage.


TYPES:
1.Centralized version control:
It has one single copy of code in the central server. developer will have to commit their changes in the code to his central server. committing a change simply means recording the changes in the central systems. good for storing large files. need a dedicated internet connection for every operation. e.g. sub version, helix core

2. distributed Version Control:
one does not necessarily rely on a central server to store all the versions of a project file. Every developer clones a copy of the main repository on their local systems. This also copies all the past versions of the code on the local system too. Therefore, the developer need not be connected to the internet to work on the code. but not good for storing large files e.g. git, mercurial, perforce.


GIT:
git is the most popular tool among all the DVCS tools. git is a version control system for tracking changes in computer files and coordinating work on those files among multiple people. It is primarily used for sources code management in software development, but it can be used to keep track of changes in any set of files.


Life cycle git:
1. working directory: the place where your project resides in your local disk. The project can be tracked by git, by using the command "git init". by doing git init, it automatically creates a hidden “. git" folder
   
3. staging area: once we are in the working directory, we must specify which files are to be tracked by git. we do not specify all files to be tracked in git, because some files could be temporary data which is being generated while execution.. to add files in the staging area, we use the command “git add."
   
5. commit: once the files are selected and are ready in the staging area, they can now be saved in the repository. Saving a file in the repository of git is known as doing a commit. When we commit a repository in git the commit is identified by a commit id. The command for initializing this process is " git commit -m" (message).
Once the file is committed, they can be pushed to a remote repository such as GitHub.


Git Commands:
a. git init: for initializing directory. 
b. git status: check status that file was added or not.
c. git add: add files to git
d. git commit: save the file to git
e. git remote add origin <profile link>: add git files to the GitHub.
f. git push: push files to our URL
g. git clone <URL>: clone the the repo
h. git pull origin master: for viewing recent changes of directory
I. git branch <name>: create branch.
j. git branch -D <name>: delete branch.
k. git checkout <name>: switching branch.
l. git log: history of commands
m. git stash: if we want to save work without committing the code. 
n. git stash -u: it we want to stash our untracked files as well.
o. git stash pop: once we are back and want to retrieve working.
p. git revert <commit ID>: reverting changes
q. git diff <ID> <ID>: check difference between two versions


Merging branches:
Once the developer has finished his code/features on his branch, the code will have to be combined with the master branch.
two ways:
1. git merger: used for remote branching
If we want to apply changes from one branch to another branch, one can use merge command. should be used on remote branches since history does not change. create a new commit, which is a merger of the two branches. syntax: git merge <source branch>

2. git rebase: use for local branch
This is an alternative to git merge command. History is based on common commit of the two branches. does not create any new commit, and results in a cleaner history syntax: git rebase <branch name>


Merge conflicts: 
merge conflicts occur when we try to merge two branches, which have the same file updated by two different developers. syntax: git merge tool :wq :q :q then again commits the file.


forking: 
a fork is a copy of a repository. Forking a repository allows us to freely experiment with changes without affecting the original project.


Git workflow / branching strategies:
1. centralized workflow: this workflow doesn’t require any other branch other than master. All the changes are directly made on the master. results in a clean, liner history.
2. featured branching: master only contains the production ready code. any development work is converted into a feature branch and then merged with a feature branch.
3. gitflow: in this workflow we have a master, a develop and the feature branches. a feature branch is never merged directly with master. It-flow combines feature and release branches to create a more structured branching strategy.
