# Git Tutorial

Welcome to the Git Tutorial! This guide provides a comprehensive overview of Git, its installation process, and how to use Git for version control.

## Table of Contents

- [What is Git?](#what-is-git)
- [Installing Git](#installing-git)
- [Setting up a Git Repository](#setting-up-a-git-repository)
- [Basic Git Commands](#basic-git-commands)
  - [git init](#git-init)
  - [git clone](#git-clone)
  - [git status](#git-status)
  - [git add](#git-add)
  - [git commit](#git-commit)
  - [git push](#git-push)
  - [git pull](#git-pull)
  - [git log](#git-log)
- [Branching in Git](#branching-in-git)
  - [git branch](#git-branch)
  - [git checkout](#git-checkout)
  - [git merge](#git-merge)
- [Conclusion](#conclusion)

## What is Git?

Git is a distributed version control system that helps developers track changes to files, collaborate with others, and manage project histories. It enables teams to work simultaneously on code, track revisions, and roll back to previous versions when needed.

## Installing Git

### On Linux

sudo apt update
sudo apt install git
On macOS
bash
Copy code
brew install git
On Windows
Download the Git installer from Git official website.
Run the installer and follow the setup instructions.
Verify your installation by running:

bash
Copy code
git --version
Setting up a Git Repository
Initialize a New Repository
bash
Copy code
git init
This creates a new .git directory in your project, making it a Git repository.

Clone an Existing Repository
To clone an existing repository from GitHub or another remote server:

bash
Copy code
git clone <repository-url>
Basic Git Commands
git init
Initializes a new Git repository in your current directory.

git clone <repository-url>
Clones a repository from a remote server like GitHub to your local machine.

git status
Shows the current status of the repository, including changes, untracked files, and files staged for commit.

bash
Copy code
git status
git add <file-name>
Adds a file to the staging area, preparing it to be committed.

bash
Copy code
git add index.html
To add all modified files:

bash
Copy code
git add .
git commit -m "<commit-message>"
Commits your staged changes to the repository with a message describing the change.

bash
Copy code
git commit -m "Add new feature"
git push
Pushes your local commits to the remote repository.

bash
Copy code
git push origin main
git pull
Fetches changes from the remote repository and merges them into your local branch.

bash
Copy code
git pull origin main
git log
Displays a list of recent commits with detailed information.

bash
Copy code
git log
Branching in Git
Branching allows you to work on different features without affecting the main project.

git branch
Lists all branches in the repository.

bash
Copy code
git branch
git checkout <branch-name>
Switches to the specified branch.

bash
Copy code
git checkout feature-branch
git merge <branch-name>
Merges the changes from the specified branch into the current branch.

bash
Copy code
git merge feature-branch
Conclusion
Git is a powerful tool that allows you to manage project history and collaborate efficiently. By mastering basic Git commands, you can track your code changes and work with others seamlessly.

For more advanced topics, consider exploring Git features such as rebasing, stashing, and working with remote repositories.

Happy coding!

less
Copy code

### Explanation:
- This Markdown (`README.md`) file provides a clean, readable format for a Git tutorial.
- The content is divided into logical sections, and the code examples are enclosed in code blocks (````bash``).
- The Table of Contents links allow for easy navigation within the file.
  
You can copy this content and save it as `README.md` in your project repository. It will render nicely on GitHub or any other Markdown viewer.



