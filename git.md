# Git
* Most widely used version control system.
* Version control systems are a category of software tools that help a software team manage changes to source code over time. Version control software keeps track of every modification to the code in a special kind of database.
* If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake.

# Pull request
*  A pull request is a way to ask another developer to merge one of your branches into their repositoy.

# Check version
  **git --version**

# Set Configuration values
  **git config --global user.name "abc"**
  **git config --global user.email "A@gmail.com"**
  
# Initializing a repository
  **git init**

# Inspecting a repository
  **git status**

* git add adds a change in the working directory to the staging area.

# Adding all files to staging are
  **git add -A**
  
* After adding files to the staging area we need to commit the changes using git commit.
  
 **git commit -m "Message"**
  
# Remove files from staging area
  **git reset -A**
  
# Cloning a repository
  **git clone <url>**

# .gitignore
Git sees the files as one of the three things. 

* Tracked - a file which has been committed.
* Untracked - a file which has not been committed.
* .gitignore - a file which Git has been explicitly told to ignore.

Ignored files are tracked in a special file named .gitignore.
.gitignore files contain patterns that are matched against file names in your repository to determine whether or not they should be ignored.

# View info about remote repository
  **git remote -v**

# Push changes to remote repository
  **git push origin master**

**git log** - To get a list of latest commits.

# Branch
A branch is a lightweight movable pointer to one of the commits. Default branch is master.

# Creating a branch
  **git branch test**

# Switching to the branch
  **git checkout test**

# Merging the branch
  **git merge test**

# Deleting a branch
  **git branch -d test**
