## Gitflow

This alternative Git branching model uses feature branches and multiple primary branches.
Then the developer creates a feature branch and delay merging it to the main branch until the feature is complete.

It is commonly used in projects with a scheduled release cycle and for Continous Delivery

In case that a problem is identified like a bug in production code, the main strategy is to create a hotfix branch, since the problem is the main branch a hotfix used this branch as the origin instead of the release branch.

Based on: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
