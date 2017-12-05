## Git branching strategies
Gitflow is really just an abstract idea of a Git workflow. This means it dictates what kind of branches to set up and how to merge them together

![Git Flow](images/git-branching-strategy.png?raw=true "Git Flow")

## master branch

The master branch serves as a main branch from where we create release tags and release the software.

## Hotfix branch

Maintenance or “hotfix” branches are used to quickly patch production releases. Hotfix branches are a lot like release branches and feature branches except they're based on master instead of develop.
<b>Note: This branch must be created from master branch</b>

## Develop branches
Each team must have seperate develop branch, all the features implemented by this team create pull request to merge changes in to develop branch.

## Feature branches
Feature branch is created by each individual developer to implement new feature, followed by they should create a pull request to integrate changes to develop branch.
Note: This branch must be created from develop branch

## Release Branches
This branch is used for integrating changes done by multiple develop branches, all the commits in this branch is throughly tested and merged into master, then the code is ready to tag to production release.
