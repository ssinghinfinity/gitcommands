Welcome to the page of git commands....

Configuring a GIT - 
git config --global user.name "Your name"
git config --global user.email "yourname@provider.com"


To view all Git Configuration
git config –list


Initializing Git Repository
-> git init

After above command executes successfully, Git will create a hidden .git directory in the current folder. This folder will contain object files which will be used by Git to store important information about the repository and keep track of changed files. Unless a folder has a .git directory inside it, Git won’t treat it as a repository.

Mapping of Local Repository to Remote Repository
-> git remote add origin repo-url
-> git remote add origin "https://github.com/ssinghinfinity/gitcommands"

