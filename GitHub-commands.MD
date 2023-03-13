# Git Command Cheat Sheet

This is just a list of the most often used git commands.


## Set Configuration values for your username and email:

```bash
git config --global user.name 
git config --global user.email
```
## Create a working directory and initialize a new git repository

```bash
cd C:\Users\UserName\FolderName
git init
```

### Clone a repository from GitHub to your machine

```bash
git clone - branch <dir_name>
```

### Working with Files

```bash
git add <filename_or_directory>
```

*add all files inside the current directory to git*

```bash
git add .
```

*see changes in the current repository*

```bash
git status
```

*staging changes in all tracked files and committing with a message*

```bash
git add -an "[message]"
```

## push an existing repository from the command line

```bash
git push -u origin main
```

## Download content from a remote repository 

```bash
git pull
```
