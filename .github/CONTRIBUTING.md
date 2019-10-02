# Contributing

Thanks for considering contributing and making our planet easier to explore!

We'd be quite excited if you'd like to contribute to gifstream! Whether you're
finding bugs, adding new features, fixing anything broken, or improving
documentation, get started by submitting an issue or pull request!

## Submitting an Issue

If you have any questions or ideas, or notice any problems or bugs, first
[search open issues](https://github.com/entryline/gifstream/issues) to see if
the issue has already been submitted. We may already be
[working on the issue](#what-were-working-on). If you think your issue is new,
you're welcome to [create a new issue](https://github.com/entryline/gifstream/issues/new).

## Pull Requests

If you want to submit your own contributions, follow these steps:

* Fork the gifstream repo.
* Create a new branch from the branch you'd like to contribute to.
* *Note:* If you're not branching from an existing feature branch, create your branch from `develop` for new features or  `master` for urgent bug fixes.
* If an issue doesn't already exist, [submit one](#submitting-an-issue).
* [Create a pull request](https://help.github.com/articles/creating-a-pull-request/) from your fork into the target branch of the `entryline/gifstream` repo.
* Be sure to [mention the issue number](https://help.github.com/articles/closing-issues-using-keywords/) in the PR description, i.e. "Fixes [#480](https://github.com/entryline/gifstream/issues/480)".
* Upon submission of a pull request, the gifstream development team will review the code.
* The request will then either be merged, declined, or an adjustment to the code will be requested.

## Guidelines

We ask that you follow these guidelines with your contributions:

### Style Guidelines

Please lint your code with `npm run lint`. Our style rules are defined in
`.stylelintrc` and `.eslintrc`. We follow a modified version of
[Standard JS Rules](https://github.com/standard/standard#the-rules), with
semi-colons. You can install linting plugins in your editor to check against
our style guides automatically:

#### Atom

* [AtomLinter](https://atomlinter.github.io/)
* [`linter-eslint`](https://atom.io/packages/linter-eslint)
* [`linter-stylelint`](https://atom.io/packages/linter-stylelint)

#### Sublime

* [SublimeLinter](http://www.sublimelinter.com/en/latest/)
* [`SublimeLinter-eslint`](https://github.com/roadhump/SublimeLinter-eslint)
* [`SublimeLinter-contrib-stylelint`](https://github.com/kungfusheep/SublimeLinter-contrib-stylelint)

### Tests

All of the unit tests for this project need to pass before your submission will
be accepted. If you add new functionality, please consider adding tests for that
functionality as well. See [Testing](doc/testing.md) for more information about
testing.

### Commits

* Make small commits that show the individual changes you are making.
* Write descriptive commit messages that explain your changes.

Example of a good commit message:

```
Improve contributing guidelines. Fixes #480

Improve contributing docs and consolidate them in the standard location https://help.github.com/articles/setting-guidelines-for-repository-contributors/
```

## What We're Working On

We use GitHub labels to organize issues we're working on. Here are the labels
we use, along with descriptions of what they mean. Click on the headings or badges below to see the GitHub issues tagged with each label.

### [`bug` ![Issues tagged with 'bug'](https://img.shields.io/github/issues-raw/entryline/gifstream/bug.svg)](https://github.com/entryline/gifstream/issues?q=is%3Aopen+is%3Aissue+label%3Abug)

Things that appear to be broken or are not working as intended.

### [`enhancement` ![Issues tagged with 'enhancement' ](https://img.shields.io/github/issues-raw/entryline/gifstream/enhancement.svg)](https://github.com/entryline/gifstream/issues?q=is%3Aopen+is%3Aissue+label%3Aenhancement)

An enhancement to an existing feature.

### [`dependencies` ![Issues tagged with 'external dependency'](https://img.shields.io/github/issues-raw/entryline/gifstream/dependencies.svg)](https://github.com/entryline/gifstream/issues?q=is%3Aopen%20is%3Aissue%20label%3A%22dependencies%22)

Issues that are waiting on something out of our control.

### [`help wanted` ![Issues tagged with 'help wanted'](https://img.shields.io/github/issues-raw/entryline/gifstream/help%20wanted.svg)](https://github.com/entryline/gifstream/issues?q=is%3Aopen+is%3Aissue+label%3A%22help%20wanted%22)

These issues might be a good place to start if you want to contribute.

### [`idea` ![Issues tagged with 'idea'](https://img.shields.io/github/issues-raw/entryline/gifstream/idea.svg)](https://github.com/entryline/gifstream/issues?q=is%3Aopen+is%3Aissue+label%3Aidea)

These are ideas, user stories, or feature requests that don't yet qualify as a new feature, probably because the specifics haven't been worked out yet.

### [`new feature` ![Issues tagged with 'new feature'](https://img.shields.io/github/issues-raw/entryline/gifstream/new%20feature.svg)](https://github.com/entryline/gifstream/issues?q=is%3Aopen+is%3Aissue+label%3A%22new%20feature%22)

These are new features to be developed at some point in the future.

### [`wontfix` ![Issues tagged with 'wontfix'](https://img.shields.io/github/issues-raw/entryline/gifstream/wontfix.svg)](https://github.com/entryline/gifstream/issues?q=is%3Aopen+is%3Aissue+label%3Awontfix)

These are issues that we don't plan to fix.
