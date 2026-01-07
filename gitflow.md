## Gitflow

This alternative Git branching model uses feature branches and multiple primary branches.
Then the developer creates a feature branch and delay merging it to the main branch until the feature is complete.

It is commonly used in projects with a scheduled release cycle and for Continous Delivery

Each new feature should be in its own branch. The feature branches use develop as their origin point. When the feature is complete it is merged to develop branch.

With the time develop will be populated with multiple features, then it is time to create a release branch off of develop. Finally after testing the release branch is merged into the main branch.

Based on: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
