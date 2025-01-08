# Contributing to Number Theory Package

👍🎉 Thank you for taking the time to contribute to our package! 🎉👍

The following is a set of guidelines for contributing to Number Theory package. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Code of Conduct

This package and everyone participating in it is governed by the our [Code of Conduct](https://github.com/UBC-MDS/DSCI524-2425-15-num-theory/blob/main/CODE_OF_CONDUCT.md).

## Prerequisites

Before you make a substantial pull request, you should always file an issue and make sure someone from the team agrees that it is a problem. If you've found a bug, create an associated issue and submit it for the team's awareness.

## How To Contribute Code to Number Theory package

### Setting Up Your Environment

Clone the package repository to you local machine. 
```
git@github.com:UBC-MDS/DSCI524-2425-15-num-theory.git
```

### Creating a Branch

Once your local environment is up-to-date, you can create a new git branch which will contain your contribution (always create a new branch instead of making changes to the main branch):

```
git switch -c <your-branch-name>
```

With this branch checked-out, make the desired changes to the package.

### Testing your Changes

Before submitting your changes to our main repository, it is recommended that you run a comprehensive test, which includes a number of tests to validate the correctness of your code.

### Creating a Pull Request

When you are happy with your changes, you can commit them to your branch by running
```
git add <modified-file>
git commit -m "Some descriptive message about your change"
git push origin <your-branch-name>
```

You will then need to submit a pull request (PR) on GitHub asking to merge your example branch into the main [DSCI524-2425-15-num-theory repository](https://github.com/UBC-MDS/DSCI524-2425-15-num-theory). For details on creating a PR see GitHub documentation [Creating a pull request](https://help.github.com/en/articles/creating-a-pull-request). You can add more details about your example in the PR such as motivation for the example or why you thought it would be a good addition. You will get feed back in the PR discussion if anything needs to be changed. To make changes continue to push commits made in your local example branch to origin and they will be automatically shown in the PR.

Hopefully your PR will be answered in a timely manner and your contribution will help others in the future.


## Attribution

These contributing guidelines were adapted from the [altair contributing guidelines](https://github.com/vega/altair/blob/main/CONTRIBUTING.md) and [dplyr contributing guidelines](https://github.com/tidyverse/dplyr/blob/master/.github/CONTRIBUTING.md).
