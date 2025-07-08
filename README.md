# Eureka-Service

## Git Workflow Guide

This guide outlines the Git workflow for contributing to this repository. Follow these steps to ensure smooth collaboration and code quality.

### 1. Create a Feature Branch  
Start by creating a new branch from the latest `master` branch using:  
`git checkout -b feature-name`

### 2. Keep `master` Updated  
Before starting work or regularly during your work, update your local `master` branch by running:  
`git checkout master`
`git pull origin master`


### 3. Rebase Your Feature Branch  
Before pushing your feature branch, rebase it on top of the updated `master` to avoid merge conflicts:  

`git checkout feature-name`
`git rebase master`


### 4. Commit and Push Your Changes  
Commit your changes with clear messages and push the feature branch to the remote repository:  

`git commit -m "Your descriptive commit message"`
`git push origin feature-name`


### 5. Create a Pull Request (PR)  
Open a PR on GitHub from your feature branch to the `master` branch.  
Use this PR title format for clarity and traceability:  
`JIRA-XX [Scope] Brief description`  
Example: `HGP-13 [Backend Dev] Add Eureka service registration`

### 6. Code Review and Merge  
Request a review from a peer.  
Address feedback by updating your branch and pushing changes.  
After approvals and successful CI/CD checks, then we can merge your PR into `master`.


---

Follow this workflow to maintain code quality and ensure smooth team collaboration.  
Happy coding!
