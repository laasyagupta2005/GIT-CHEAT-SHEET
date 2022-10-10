# KNOW ABOUT GIT AND ITS WORKFLOW

Git is a distributed version control system that helps developers collaborate on projects of any scale.

## WHAT IS A DISTRIBUTED VERSION CONTROL SYSTEM?

A distributed version control system is a system that helps you keep track of changes you've made to files in your project.

This change history lives on your local machine and lets you revert to a previous version of your project with ease in case something goes wrong.

Git makes collaboration easy. Everyone on the team can keep a full backup of the repositories they're working on on their local machine. Then, thanks to an external server like BitBucket, GitHub or GitLab, they can safely store the repository in a single place.

This way, different members of the team can copy it locally and everyone has a clear overview of all changes made by the whole team.

## GIT COMMANDS

### GIT BASICS

| Command | Description |
| - | - |
| `git init`              | initialize a Git repo |
| `git add filename_here` | adds a file in the staging area |
| `git add .`| adds all files in the staging area |
| `git status`| List which files are staged, unstaged, and untracked. |
| `git clone <repo>`| Clone repo located at <repo> onto local machine. |
| `git commit -m "<message>"`| commit changes with a message. |
| `git log`| Display the entire commit history using the default format. |
| `git diff`| Show unstaged changes between your index and working directory. |
| `git branch`| List all of the branches in your repo. |
| `git branch <branch-name>`| Create a new branch with the name 'branch-name'. |
| `git checkout <branch>`| Check out to an existing branch named 'branch' |
| `git remote add <name> <url>`| Create a new connection to a remote repo. After adding a remote, you can use 'name' as a shortcut for 'url' in other commands. |
| `git push <remote> <branch>`| Pushes the current branch to the specified remote |
| `git pull <remote> <branch>`| Fetches and merges changes from specified remote and branch into local |
| `git fetch <remote> <branch>`| Fetches a specific 'branch' from the repo. Leave off 'branch' to fetch all remote refs. |

### GIT CONFIG

| Command | Description |
| - | - |
| `git config --global user.name "john"`              | Set user name |
| `git config --global user.email "john@example.com"` | Set user email |
| `git config --global alias. <alias-name> <git-command>`| Creates shortcut for a Git command |
| `git config --global --edit`| Open the global configuration file in a text editor for manual editing. |
| `git config --system core.editor <editor>`| Set text editor used by commands for all users on the machine. <editor> arg should be the command that launches the desired editor |
