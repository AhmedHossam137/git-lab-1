# Git Questions and Answers

## What is Git?
Git is a distributed version control system that tracks changes in any set of computer files, usually used for coordinating work among programmers collaboratively developing source code during software development. Git was created by Linus Torvalds in 2005 for development of the Linux kernel. It allows multiple developers to work together on non-linear development through features like branching and merging.

## Is Git the same as GitHub? 
False. Git is a version control system, while GitHub is a cloud-based hosting service that lets you manage Git repositories. GitHub provides a web-based graphical interface and additional collaboration features like access control, bug tracking, feature requests, task management, and wikis for every project.

## What is the command to get the installed version of Git?
```
git --version
```

## Which option should you use to set the default user name for every repository on your computer?
--global

## What is the command to set the user email for the current repository?
```
git config user.email
```

## What is the command to add all files and changes of the current folder to the staging environment of the Git repository?
```
git add --all
```

## What is the command to get the current status of the Git repository?
```
git status
```

## What is the command to initialize Git on the current repository?
```
git init
```

## Git automatically adds new files to the repository and starts tracking them?
False. Git does not automatically track new files. You must explicitly add new files to the staging area using commands like `git add <filename>` or `git add .` before they can be committed.

## What is the command to commit the staged changes for the Git repository?
```
git commit
```

## What is the command to commit with the message "New email":
```
git commit -m "New email"
```

## What is the command to view the history of commits for the repository?
```
git log
```

## In Git, a branch is:
A separate version of the main repository

## What is the command to create a new branch named "new-email"?
```
git branch new-email
```

## What is the command to move to the branch named "new-email"?
```
git checkout new-email
```
(Note: In newer versions of Git, you can also use `git switch new-email`)

## What is the command to merge the current branch with the branch "new-email"?
```
git merge new-email
```
