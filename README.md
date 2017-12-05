## Git branching stratagies
Gitflow is really just an abstract idea of a Git workflow. This means it dictates what kind of branches to set up and how to merge them together

![Git Flow](images/git-branching-strategy.png?raw=true "Git Flow")

## How it works
Instead of a single master branch, this workflow uses two branches to record the history of the project. The master branch stores the official release history, and the develop branch serves as an integration branch for features. It's also convenient to tag all commits in the master branch with a version number.

The first step is to complement the default master with a develop branch. A simple way to do this is for one developer to create an empty develop branch locally and push it to the server:
