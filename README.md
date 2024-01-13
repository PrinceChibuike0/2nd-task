# 2nd-task

 # What is version control
A system called version control keeps track of modifications made to a project or collection of files over time. It logs changes, makes it easier to coordinate various file versions, and enables several contributors to work together on a project. The following are version control's main goals: 

Track Changes: Over time, changes made to files are meticulously documented by version control systems (VCS). Users can comprehend the project's development because every change, addition, or deletion is recorded.


Collaboration: A project can have several developers working on it at once. Version control offers a way to combine changes made by several participants, which facilitates effective collaboration.

# Difference between git and github

Git is a distributed version control system designed for tracking changes in source code locally. It operates on a developer's machine and allows for version control and history tracking without the need for an internet connection.

GitHub is a web-based platform that hosts Git repositories in the cloud. It serves as a collaborative environment, offering features like issue tracking, pull requests, and project management tools. GitHub enhances Git by providing a centralized hub for remote collaboration.

Key Differences:

Git is local, GitHub is remote.
Git focuses on version control and tracking changes.
GitHub is a platform for hosting, collaboration, and project management.
Git operates through the command line, while GitHub provides a web interface.

# other github alternatives 

- GitLab 
- Bitbucket
- SourceForge

# Difference between git fetch and git pull 

 - git fetch: retrieves updates from a remote repository without automatically merging them into local branches. It allows you to review changes before deciding to merge. 

- git pull: fetches and merges changes from a remote repository into local working branch. It automatically combines the fetched changes with your local branch.

- Use git fetch: when you want to check for updates from the remote repository but prefer to review changes before merging.

 - Use git pull: when you want to fetch and merge changes from the remote repository into local working branch in a single command

 # Git rebase and the command for it

  Git command allows you to modify the commit history of a branch by moving, combining, or deleting existing commits. Unlike git merge, which creates new merge commits, git rebase rewrites the commit history, resulting in a more linear and cleaner timeline. 
 git rebase -- (***)	This executes a command line shell script for each marked commit during playback. 




