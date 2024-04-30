Thank you for considering contributing to nsbi.

If you have a new feature/bug report, make sure you create an [issue](https://github.com/handley-lab/nsbi/issues), and consult existing ones first, in case your suggestion is already being addressed.

If you want to go ahead and create the feature yourself, you should fork the repository to you own github account and create a new branch with an appropriate name. Commit any code modifications to that branch, push to GitHub, and then create a pull request via your forked repository. More detail can be found [here](https://gist.github.com/Chaser324/ce0505fbed06b947d962).

Note that a [code of conduct](https://github.com/handley-lab/nsbi/blob/master/CODE_OF_CONDUCT.md) applies to all spaces managed by the nsbi project, including issues and pull requests. 

## Contributing - `pre-commit`

nsbi uses black and isort to maintain a consistent style. To speed up linting, contributors can optionally use pre-commit to ensure their commits comply.

First, ensure that pre-commit, black and isort are installed:
```
pip install pre-commit black isort
```
Then install the pre-commit to the .git folder:
```
pre-commit install
```
This will check changed files, and abort the commit if they do not comply. To uninstall, run:
```
pre-commit uninstall
```
