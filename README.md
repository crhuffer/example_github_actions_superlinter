# Example Github Actions Superlinter

[![GitHub Super-Linter](https://github.com/crhuffer/example_github_actions_superlinter/workflows/Lint%20Code%20Base/badge.svg)](https://github.com/marketplace/actions/super-linter)

## Design Decisions

### Focus on server side hooks but provide client side hooks
We want server side hooks because it seems like the only way to ensure that the shared code meets our standards.
Client side hooks would be up to the contributors to set up correctly, and if they are not used properly, it would allow code to be pushed that violates the standards.
I assume that we will also provide client side hooks to help developers keep their work clean to limit the friction at the push.

## Resources

* [medium: getting started with git hooks](https://medium.com/@f3igao/get-started-with-git-hooks-5a489725c639)
* [github/super-linter](https://github.com/github/super-linter)
* [pre-commit.com/hooks.html](https://pre-commit.com/hooks.html)
* [stackoverflow: enforcing pep-8ish formatting in github commits](https://stackoverflow.com/questions/9799209/enforcing-pep-8ish-formatting-in-github-commits)
* [stackoverflow: how to set up actions in github for new users](https://stackoverflow.com/questions/62271879/how-to-set-up-actions-in-github-for-new-user/62458603#62458603)
* [github.blog: introducing super-linter](https://github.blog/2020-06-18-introducing-github-super-linter-one-linter-to-rule-them-all/)
* [towarddatascience: pre-commit hooks you must know](https://towardsdatascience.com/pre-commit-hooks-you-must-know-ff247f5feb7e)
