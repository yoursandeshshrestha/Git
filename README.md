# Git & GitHub 😺
<li> Git is a distributed version control system (DVCS) that allows you to track changes in your codebase. </li>
<li> GitHub is a web-based platform that hosts Git repositories and provides additional features for collaboration and project management. </li>


## How to setup git 🚀
<li>Install Git and Open Git Bash:</li>
<li>If you haven't already installed Git, you can download and install it from the official website: Once installed, open Git Bash</li>

## Configure Git: 😇
<li>1. Before using Git, you should configure your username and email.</li>
<li>2. go to terminal and type this command, use your github account info here</li>

* `git config --global user.name "Your Name"`
* `git config --global user.email "youremail@example.com"`

## Connecting and pushing repo to github 🛠️
<li>Open your project and Type this steps in VS code terminal</li>
<li>but first you need to create a repo in git hub account</li>

* `git init` <br>
* `git add README` <br>
* `git commit -m "first commit'`
* `git branch -M main`
* `git remote add origin "your repo link"`
* `git push -u origin main`

## Cloning a repo into local 👬

* `git clone "your repo link"`

## Most Important Git Commands: ⭐
**git init:** `Initializes a new Git repository in the current directory.`<br>
**git clone [url]:** `Clones a remote repository to your local machine.`<br>
**git add [file]:** `Adds a file or changes in a file to the staging area.`<br>
**git commit -m "message":** `Commits staged changes with a descriptive message.`<br>
**git status:** `Shows the status of your working directory and staging area.`<br>
**git diff:** `Shows the differences between the working directory and the staging area.`<br>
**git log:** `Displays the commit history.`<br>
**git branch [branch_name]:** `Creates a new branch or lists existing branches.`<br>
**git checkout [branch_name]:** `Switches to the specified branch.`<br>
**git merge [branch_name]:** `Merges changes from the specified branch into the current branch.`<br>
**git pull:** `Fetches changes from the remote repository and merges them into the current branch.`<br>
**git push:** `Pushes committed changes to the remote repository.`<br>

## Most Important GitHub Commands: ⭐
**git remote add origin [url]:** `Connects your local repository to a remote repository on GitHub.`<br>
**git push -u origin [branch_name]:** `Pushes the specified branch to GitHub, establishing a tracking relationship.`<br>
**git pull origin [branch_name]:** `Pulls changes from a remote repository on GitHub into your local repository.`<br>
**git fetch:** `Fetches changes from the remote repository on GitHub without merging them into your local branch.`<br>
**git clone [url]:** `Clones a repository from GitHub to your local machine.`<br>
**git fork:** `Forks a repository on GitHub, creating a copy under your account.`<br>
**git pull-request:** `Opens a pull request on GitHub, allowing you to propose changes to a repository.`<br>
**git issue:** `Manages issues on GitHub repositories.`<br>
**git blame [file]:** `Shows who last modified each line of a file and in which commit.`<br>
**git tag [tag_name]:** `Tags a specific commit in your repository.`<br>

## My personal steps to clone github repo into my local storage 🔖 

* `cd desktop`
* `git clone [Repo Link]`
* `cd [project name]`
* `git init`
* `git add . (. <- basically add all file) or you can upload any single file. for example index.html`
* `git commit -m "Added html file" (this is message u upload while pushing commit)`
* `git push`

## Remove Git from folder 🗑 

**On Windows (using PowerShell)**
* `Remove-Item .git -Recurse -Force`

**On Windows (using Command Prompt)**
* `rmdir /s .git`

**On Unix/Linux/Mac:**
* `rm -rf .git`
