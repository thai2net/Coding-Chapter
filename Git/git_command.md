# Git
Git is a distributed version control system that allows you to track changes in files and collaborate with others on software development projects.

# Create new or an existing repository
## Create a new repository on the command line
```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/thai2net/VueJS-Sample.git
git push -u origin main
```

## Push an existing repository from the command line
```
git remote add origin https://github.com/thai2net/VueJS-Sample.git
git branch -M main
git push -u origin main
```
# Git commands

## Initializes a new Git repository in the current directory
```
 git init
```
## Creates a copy of a remote repository on your local machine
```
 git clone [repository]
```
## Adds a file or directory to the staging area, preparing it to be committed
```
 git add [file]
```
## Commits the changes in the staging area to the repository with a descriptive message
```
 git commit -m "[message]"
```
## Shows the current status of your repository, including modified files and files in the staging area
```
 git status
```
## Pushes committed changes to a remote repository
```
 git push
```
## Fetches and merges changes from a remote repository into your local repository
```
git pull
```
## Lists all branches in the repository
```
git branch
```
## Creates a new branch
```
git branch [branch-name]
```
## Switches to the specified branch
```
git checkout [branch-name]
```
## Merges the changes from the specified branch into the current branch
```
git merge [branch-name]
```
## Displays a history of commits in the repository
```
git log
```

These are just a few basic Git commands, and there are many more available for various purposes. You can use git --help or git [command] --help for more information on a specific command or refer to the Git documentation for detailed usage instructions.
