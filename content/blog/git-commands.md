---
title: "Git Commands"
date: 2023-07-28T11:18:21-04:00
draft: false
---

## Basic Git Commands

**.git-init**

Initializes a new Git repository in your project directory. This command sets up the necessary files and folders to start tracking changes.

```powershell
git init 
```

---

**.git-clone**

Downloads a copy of an existing Git repository to your local machine. Replace [repository_url] with the URL of the GitHub repository you want to clone.

```powershell
git clone [repository_url]
```
---


**.git-add**

Adds changes made to a specific file to the staging area. Use this command to prepare files for the next commit.

```powershell
git add [file]
```

Adds all changes made to any tracked files in the current directory to the staging area.

```powershell
git add .
```

---

**.git-commit**

Commits the changes from the staging area to the Git repository. A commit message is required to describe the changes made in the commit.

```powershell
git commit -m "[commit_message]"
```

---

**.git-push**

Uploads your local commits to the remote GitHub repository. It is used to share your changes with others.

```powershell
git push
```
---

**.git-pull**

Downloads and integrates changes from the remote GitHub repository into your local repository. Use this command to update your local codebase with the latest changes from the remote.

```powershell
git pull
```
---

**.git-status**

Shows the status of your working directory and staging area. It displays information about which files have been modified, added, or deleted.

```powershell
git status
```
---

**.git-log**

Displays a history of commits in the repository, showing commit messages, authors, dates, and commit IDs.

```powershell
git log
```
---

**.git-branch**

Lists all the branches in your local repository. The branch with an asterisk (*) next to it is the currently checked-out branch.

```powershell
git branch
```
---

**.git-checkout**

Switches to the specified branch. Replace [branch_name] with the name of the branch you want to switch to.

```powershell
git checkout [branch_name]
```
---

**.git-merge**

Merges the changes from the specified branch into the current branch. It is used to combine different lines of development.

```powershell
git merge [branch_name]
```
---

**.git-remote**

Lists the remote repositories linked to your local repository. You should see the URL of the GitHub repository you cloned from.

```powershell
git remote -v
```

---

**.git-remote add**

Adds a new remote repository with a custom name. This is useful when you want to link your local repository to multiple remote repositories.

```powershell
git remote add [remote_name] [repository_url]
```