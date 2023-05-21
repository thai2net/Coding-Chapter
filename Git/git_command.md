# Create new or an existing repository
## Create a new repository on the command line
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/thai2net/VueJS-Sample.git
git push -u origin main

## Push an existing repository from the command line
git remote add origin https://github.com/thai2net/VueJS-Sample.git
git branch -M main
git push -u origin main

Git is a distributed version control system that allows you to track changes in files and collaborate with others on software development projects. Here are some commonly used Git commands:

1. git init: Initializes a new Git repository in the current directory.
2. git clone [repository]: Creates a copy of a remote repository on your local machine.
3. git add [file]: Adds a file or directory to the staging area, preparing it to be committed.
4. git commit -m "[message]": Commits the changes in the staging area to the repository with a descriptive message.
5. git status: Shows the current status of your repository, including modified files and files in the staging area.
6. git push: Pushes committed changes to a remote repository.
7. git pull: Fetches and merges changes from a remote repository into your local repository.
8. git branch: Lists all branches in the repository.
9. git branch [branch-name]: Creates a new branch.
10. git checkout [branch-name]: Switches to the specified branch.
11. git merge [branch-name]: Merges the changes from the specified branch into the current branch.
12. git log: Displays a history of commits in the repository.

These are just a few basic Git commands, and there are many more available for various purposes. You can use git --help or git [command] --help for more information on a specific command or refer to the Git documentation for detailed usage instructions.
