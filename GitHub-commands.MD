# Git Command Cheat Sheet

### Initialize a new git repository:
git init

### Set Configuration values for your username and email:
git config --global user.name <your-name>
git config --global user.email <your-email>

### Clone a repository from GitHub to your machine
git clone - branch <repository-url> <dir_name>

### Working with Files
git add <filename_or_directory>

* add allfiles inside current directory to git
git add .

*see changes in current repository
git status

*staging changes in all tracked files and commiting with a message
git add -an "[message]"

*push the commited changes to a remote repository
git push <remote> <branch>

*download content from a remote repository
git pull <remote>
