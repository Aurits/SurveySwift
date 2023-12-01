# Contributing to SurveySwift

First off, thank you for considering contributing to SurveySwift! It's people like you that make SurveySwift such a great tool.

## Where do I go from here?

If you've noticed a bug or have a feature request, make an issue on GitHub. If you'd like to contribute a feature or bug fix, you can fork our repository and submit a pull request. We really appreciate the community's help in improving and extending SurveySwift!

## Fork & create a branch

If this is something you think you can fix, then fork SurveySwift and create a branch with a descriptive name.

A good branch name would be (where issue #325 is the ticket you're working on):

```bash
git checkout -b 325-add-japanese-translations
```

## Implement your fix or feature

At this point, you're ready to make your changes! Feel free to ask for help; everyone is a beginner at first 😸

## Make a Pull Request

At this point, you should switch back to your master branch and make sure it's up to date with SurveySwift's master branch:

```bash
git remote add upstream git@github.com:aurits/SurveySwift.git
git checkout master
git pull upstream master
```

Then update your feature branch from your local copy of master, and push it!

```bash
git checkout 325-add-japanese-translations
git rebase master
git push --set-upstream origin 325-add-japanese-translations
```

Finally, go to GitHub and [make a Pull Request](https://help.github.com/articles/creating-a-pull-request/) 😃

## Keeping your Pull Request updated

If a maintainer asks you to "rebase" your PR, they're saying that a lot of code has changed, and that you need to update your branch so it's easier to merge.

To learn more about rebasing in Git, there are a lot of [good](https://git-scm.com/book/en/v2/Git-Branching-Rebasing) [resources](https://www.atlassian.com/git/tutorials/merging-vs-rebasing) but here's the suggested workflow:

```bash
git checkout 325-add-japanese-translations
git pull --rebase upstream master
git push --force-with-lease 325-add-japanese-translations
```

## Merging a PR (maintainers only)

A PR can only be merged into master by a maintainer if:

- It is passing CI.
- It has been approved by at least two maintainers. If it was a maintainer who opened the PR, only one extra approval is needed.
- It has no requested changes.
- It is up to date with current master.

Any maintainer is allowed to merge a PR if all of these conditions are met.

## Thank you!

Thanks again for your contribution, we really appreciate it! 🎉
