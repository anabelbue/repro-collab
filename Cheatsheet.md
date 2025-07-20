### Cheat Sheet: Collaborative Writing on GitHub

**GitHub**:  A kind of cloud storage built around the version control system *git*.  
Like Dropbox, it lets you store and share your project files online, but it’s specifically designed for collaboration and version control.
*Git* helps to track and manage the development of your files in a structured way, so you can recall earlier versions when needed. 
In this workshop, you only work online in GitHub. 
However, in typical collaborative projects, you'll also use git locally on your computer to track progress (through *commits*), and then upload ("push") your current version to GitHub so others can access and contribute.

**Commit**: The central unit of version control in git. 
A commit is like a snapshot of your entire project at a certain point in time, saving all changes since the last commit. 
Git tracks these changes line by line, so you can compare different versions and see exactly what was added, removed, or modified. 
The sequence of commits forms the *commit history*, showing how your project has evolved and allowing you to restore earlier versions if needed. 
To keep things organized, you should create a commit whenever you reach a (small) milestone and briefly describe your changes in a *commit message*. 
This helps you and your collaborators see who changed what and when.

**Repository**: The central project folder in GitHub.
It stores all files, version history, and collaboration tools (like issues, pull requests, and branches).
In collaborative writing, the repository is like your shared document workspace. 

**Fork**: A personal copy of a repository, saved under your own GitHub account.
In typical collaborative writing projects, forking is usually *not* needed as collaborators can work directly within the shared repository (e.g., in their own branch).
In this workshop, you are asked to fork the repository for technical reasons, so you can work on your own copy instead of editing the original workshop repository directly.
The original repository you forked from is also called the upstream repository.

**Branch**: A parallel version of the project, created within the same repository.
The main branch represents the current official version of the project.
Creating additional, separate branches allows collaborators to work on changes without affecting the main version until their work is ready to be added.
After finishing work in a branch, collaborators can open a pull request to suggest adding their changes to the main branch.
*Note*: Forks and branches are technically similar but differ in permissions. Branches are part of the shared repository and can be edited by anyone with write access. Forks create a separate repository under your control, with permissions managed independently from the upstream repository. Forks are typically used when you don’t have write access to the upstream repository. 

**Pull Request (PR)**: A way to suggest changes to a project.
Pull requests can be made within the same repository (e.g., from a separate branch into the main branch) or from a fork to a branch in the upstream repository.
In both cases, they request that your changes are “pulled” into the main branch the target branch.
A pull request lets others review your changes, give feedback, and approve them before they are added to the main branch.

**Issue**: A way to track tasks, ideas, or bugs within a specific repository.
In collaborative writing, issues help structure work on the text (e.g., outlining sections), discuss revisions, or assign writing tasks.

For example, you can: 
- Create checklists by typing - [ ] followed by your task
- Mention people with @username to notify them directly
- Reference issues or PRs using #issue-number or #PR-number



