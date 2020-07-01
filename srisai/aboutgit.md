# Everything About Git and Github

# Git:

Git is distributed version control system.It contains local repository which can be accessed anywhere even without network.
There are 4 fundamentals of Git workflow:
1. Workspace - which is our local directory
2. Index- also called stage
3. Local Repository- HEAD
4. Remote Repository

If you consider a file in your workspace it can be in 3 possible states:
1. It can be committed which means latest changes to the file are safely stored in local repository .
2. It could be modified and changes are not saved in local Repository so locally modified.
3. It can be staged means that it can be considered in next commit.

# git commands :

1. git init     : initializes a repository.
2. git checkout : checks out a branch from repository into the working directory.
3. git add      : adds a change in a file to a change set.
4. git commit   : commits a change set from the working directory into the repository.
5. git branch   : creates a new branch from the current HEAD (working directory).
6. git checkout -b : creates a new branch from the current HEAD, and switches the working directory to the new branch.
7. git diff     : shows the difference of between the working directory and the given branch.
8. git checkout : checks out files from the given branch into the working directory.
9. git merge    : merges the given branch into the current branch.
10. git merge -abort : aborts a merge that resulted in conflicts.
11. git clone   : creates a “clone” of a remote repository.
12. git remote add : adds a remote repository named with the given connection URL.
13. git fetch   : fetches changes to the remote tracking branch for from remote repository .
14. git pull    : fetches, followed by a merge.
15. git push    : pushes a change from the local branch through the remote tracking branch to the remote repository.
16. git status  : often give valuable hints on what to do next.


# Github:

Github is a web-based platform used for version control. Git simplifies the process of working with other people and makes it easy to collaborate on projects.
Team members can work on files and easily merge their changes in with the master branch of the project. Git & GitHub skill has slowly made its way from preferred
skills to must have skills in multiple job roles.It is a webservice where we can do git things.

* Github repository:
A repository is a storage space where your project exits. It can be local to a folder on your computer.We can keep code files, text files, images or any kind of a
file in a repository.We need a GitHub repository when we have done some changes and are ready to be uploaded. This GitHub repository acts as your remote repository.

* Branches:
Branches help us to work on different versions of a repository at one time.we want to add a new feature and we are afraid at the same time whether 
to make changes to your main project or not. Then branches helps us to move back and forth between the different states/versions of a project.
We can create a new branch and test the new feature without affecting the main branch. Once we are done with it, you can merge the changes from new branch to the main branch.

# Forking:
The term fork means producing a personal copy of someone else project.Git Fork means you just create a copy of the main repository of a project source code to your own GitHub profile.
Steps for forking:
1. click the fork button present on left right corner.

# Cloning:
The term clone means getting a local copy of the code present in the repository. After cloning  you can then do whatever changes you like in the code and then you
can pull the changes back to the repository.Suppose we want to use some code which is present in a public repository, you can directly copy the contents by cloning or downloading.
steps for cloning:
1. Click the clone or download button and then copy the HTTPS url .
2. Using Git on your local machine, clone your fork using the URL you just copied: git clone url.
3. Navigate to local repository: cd nameofrepository.
4. Use git remote -v to show your current remotes. You should see the URL of your fork next to the word "origin".
5. create or update files in  the local repository.
6. After making a set of changes, use git add -A to stage your changes and git commit -m "DESCRIPTION" to commit them.
7. Push the changes to the fork using git push origin BRANCHNAME.
8. Begin Pull Request.


# Pull Request:
Pull command is the most important command in GitHub. It tell the changes done in the file and request other contributors to view it as well as merge it with the master branch.
Once the commit is done, anyone can pull the file and can start a discussion over it. Once its all done, you can merge the file. Pull command compares the changes which are done 
in the file and if there are any conflicts, you can manually resolve it.
Steps:
1. Click the ‘Pull requests’ tab.
2. Click ‘New pull request’.
3. Once you click on pull request, select the branch and click ‘readme- changes’ file to view changes between the two files present in our repository.
4. Click “Create pull request”.
5. Enter any title, description to your changes and click on “Create pull request”.




