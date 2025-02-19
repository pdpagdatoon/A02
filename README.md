# A02
# Part 1
## 1. Install Git
Download **Git** using https://git-scm.com/ and install
   
## 2. Set Up Git
1. Configure your Git username and email using "git config --global user.name "Your Name"", then "git config --global user.email "your.email@example.com""
2. To check your configuration: git --version

## 3. Install VS Code
1. Download VS Code from https://code.visualstudio.com/ and install.
   
## 4. Set Up Git in VS Code
1. Open VS Code and install the **GitHub Pull Requests and Issues** extension from the Extensions Marketplace.
2. Open VS Code’s built-in terminal
3. Navigate to your project folder: cd path/to/your/project

## 5. Initialize a Git Repository
1. Initialize a new **repository** using "git init"
2. Add all files to the repository using "git add ."
3. **Commit** the changes using "git commit -m "Initial commit""

## 6. Connect to GitHub
1. Create a **GitHub** account at https://github.com.
2. Create a new repository on GitHub.
3. Link your local repository to GitHub using "git remote add origin https://github.com/your-username/your-repository.git"
4. **Push** your code to GitHub using "git push -u origin main:"

## 7. Cloning a Repository
1. Copy the repository URL from GitHub.
2. **Clone** it using "git clone https://github.com/your-username/your-repository.git"

## 8. Making Changes and Pushing Updates
1. Make changes to your files in VS Code.
2. Stage changes using "git add ."
3. **Commit** changes using "git commit -m "Updated feature""
4. Push changes to GitHub: git push origin main

## 9. Creating and Merging Branches
1. Create a new branch "git checkout -b feature-branch"
2. Switch to the new branch using "git checkout feature-branch"
3. **Merge** changes back into the main branch "git checkout main", "git merge feature-branch"
4. Push the updated main branch to GitHub: git push origin main

## 10. Pulling Changes from GitHub
Pull the latest changes before working with "git pull origin main"


# Part 2
## **Word Definitions** 
**Branch** - A branch is a parallel version of a repository. 
**Clone** - A copy of a repository that lives on your computer locally.\
**Commit** - An individual change to a file and usually contain a commit message which is a brief description of what changes were made.\
**Fetch** - Adding changes from the remote repository to your local working branch without committing them.\
**GIT** - Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.\
**Github** - GitHub is a proprietary developer platform that allows developers to create, store, manage, and share their code.\
**Merge** - Merging takes the changes from one branch , and applies them into another. This happens as a "pull request" or through the command line.
**Merge Conflict** - A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.\
**Push** - Send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.\
**Pull** - Fetching in changes and merging them.\
**Remote** - The version of a repository or branch \
**Repository** - Ccontains all of the project files, and stores each file's revision history. They can have multiple collaborators and can be either public or private.

References:
https://code.visualstudio.com/docs/sourcecontrol/intro-to-git
https://code.visualstudio.com/docs/sourcecontrol/github
https://docs.github.com/en/get-started
https://docs.github.com/en/get-started/learning-about-github/github-glossary#repository
