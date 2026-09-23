# A02

# Git and GitHub Tutorial

## Introduction

Git and GitHub are tools used to manage and store projects. Git tracks changes made to files, while GitHub allows repositories to be stored and shared online. WebStorm can be used to create and edit projects while also providing access to Git commands through its terminal. This tutorial explains the basic process of using Git, GitHub, and WebStorm.



# Part 1: Directions on Using WebStorm

### Step 1: Download WebStorm

Download WebStorm from the official JetBrains website:

https://www.jetbrains.com/webstorm/

Install WebStorm and open it.

### Step 2: Create a Project

1. Select **New Project**.
2. Choose where you want to save the project.
3. Enter a project name.
4. Click **Create**.

### Step 3: Create and Edit Files

Use the file explorer on the left side of WebStorm to create new files. Click on a file to open it and make changes in the editor.

### Step 4: Use the Terminal

WebStorm has a built-in terminal at the bottom of the program. The terminal can be used to enter Git commands without leaving WebStorm.



# Part 2: Using Git

### Step 1: Install Git

Download Git from:

https://git-scm.com/downloads

After installing it, open the WebStorm terminal and type:

`git --version`

This checks if Git was installed correctly.

### Step 2: Set Up Git

Enter your name and email:

`git config --global user.name "Your Name"`

`git config --global user.email "your@email.com"`

This tells Git who is making the changes.

### Step 3: Create a Repository

Open your project in WebStorm and use:

`git init`

This starts Git in your project folder.

### Step 4: Check Your Files

Use:

`git status`

This shows which files have been changed or added.

### Step 5: Add and Commit Changes

Add your files with:

`git add .`

Then create a commit:

`git commit -m "Task: Create Repository"`

A commit saves your changes and gives you a record of what was changed.

### Step 6: Connect to GitHub

After creating your GitHub repository, connect it to your local project:

`git remote add origin https://github.com/yourUCID/A02.git`

### Step 7: Push Your Changes

Upload your commits to GitHub with:

`git push -u origin main`

This sends your local changes to your GitHub repository.

### Step 8: Pull and Fetch

Use:

`git pull`

to download and combine changes from GitHub.

Use:

`git fetch`

to download information about changes without combining them with your current files.

Good commit messages can include:

`Task: Create Repository`

`Feature: added workflow for using github`

`Fix: changed readme.md for definition of terms`



# Part 3: Using GitHub

### Step 1: Create a GitHub Account

Go to:

https://github.com/

Create an account if you do not already have one.

### Step 2: Create the A02 Repository

1. Log into GitHub.
2. Click **+** and select **New repository**.
3. Name the repository **A02**.
4. Make sure the **A** is capitalized.
5. Create the repository.

Your repository URL should look like:

`https://github.com/yourUCID/A02`

### Step 3: Add Your README

The `README.md` file explains your project and can use Markdown formatting such as headings, lists, bold text, and code.

Add this tutorial and the glossary to your README.

### Step 4: Upload Your Work

After making changes, use:

`git add .`

`git commit -m "Feature: added workflow for using github"`

`git push`

Your changes should now appear on GitHub.

### Step 5: Submit Your Repository

Copy your A02 repository link and submit it to Canvas.



# Part 4: Glossary

* **Branch** - A separate version of a repository used to work on changes without changing the main branch.

* **Clone** - Creates a copy of a repository from GitHub on your computer.

* **Commit** - Saves a version of your changes in Git.

* **Fetch** - Downloads information about changes from a remote repository without merging them.

* **GIT** - A version control system used to track changes to files and projects.

* **Github** - An online platform used to store, manage, and share Git repositories.

* **Merge** - Combines changes from different branches.

* **Merge Conflict** - Happens when Git cannot automatically combine changes because conflicting changes were made.

* **Push** - Uploads local commits and changes to a remote repository.

* **Pull** - Downloads changes from a remote repository and combines them with the local project.

* **Remote** - A repository stored somewhere other than your local computer, such as GitHub.

* **Repository** - A location where project files and their Git history are stored.

---

# References

Git. (n.d.). *Git documentation*. https://git-scm.com/doc

GitHub. (n.d.). *GitHub documentation*. https://docs.github.com/

GitHub. (n.d.). *About GitHub and Git*. https://docs.github.com/en/get-started/start-your-journey/about-github-and-git

GitHub. (n.d.). *Git basics*. https://docs.github.com/en/get-started/learning-to-code/getting-started-with-git

GitHub. (n.d.). *Managing branches*. https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-branches

JetBrains. (n.d.). *WebStorm documentation*. https://www.jetbrains.com/help/webstorm/

JetBrains. (n.d.). *Git integration in WebStorm*. https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html

Atlassian. (n.d.). *Git tutorials*. https://www.atlassian.com/git/tutorials

W3Schools. (n.d.). *Git tutorial*. https://www.w3schools.com/git/
