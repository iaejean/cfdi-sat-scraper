# Contributing

Contributions are welcome. We accept pull requests on [GitHub](https://github.com/phpcfdi/cfdi-sat-scraper).

This project adheres to a
[Contributor Code of Conduct](https://github.com/phpcfdi/cfdi-sat-scraper/blob/master/CODE_OF_CONDUCT.md).
By participating in this project and its community, you are expected to uphold this code.

## Team members

* [Cesar Aguilera](https://github.com/blacktrue) - original author and maintainer
* [GitHub contributors](https://github.com/phpcfdi/cfdi-sat-scraper/graphs/contributors)

## Communication Channels

You can find help and discussion in the following places:

* GitHub Issues: <https://github.com/phpcfdi/cfdi-sat-scraper/issues>

## Reporting Bugs

Bugs are tracked in our project's [issue tracker](https://github.com/phpcfdi/cfdi-sat-scraper/issues).

When submitting a bug report, please include enough information for us to reproduce the bug.
A good bug report includes the following sections:

* Expected outcome
* Actual outcome
* Steps to reproduce, including sample code
* Any other information that will help us debug and reproduce the issue, including stack traces, system/environment information, and screenshots

**Please do not include passwords or any personally identifiable information in your bug report and sample code.**

## Fixing Bugs

We welcome pull requests to fix bugs!

If you see a bug report that you'd like to fix, please feel free to do so.
Following the directions and guidelines described in the "Adding New Features"
section below, you may create bugfix branches and send us pull requests.

## Adding New Features

If you have an idea for a new feature, it's a good idea to check out our
[issues](https://github.com/phpcfdi/cfdi-sat-scraper/issues) or active
[pull requests](https://github.com/phpcfdi/cfdi-sat-scraper/pulls)
first to see if the feature is already being worked on.
If not, feel free to submit an issue first, asking whether the feature is beneficial to the project.
This will save you from doing a lot of development work only to have your feature rejected.
We don't enjoy rejecting your hard work, but some features just don't fit with the goals of the project.

When you do begin working on your feature, here are some guidelines to consider:

* Your pull request description should clearly detail the changes you have made.
* Follow our code style using `squizlabs/php_codesniffer` and `friendsofphp/php-cs-fixer`.
* Please **write tests** for any new features you add.
* Please **ensure that tests pass** before submitting your pull request. We have Travis CI automatically running tests for pull requests. However, running the tests locally will help save time.
* **Use topic/feature branches.** Please do not ask us to pull from your master branch.
* **Submit one feature per pull request.** If you have multiple features you wish to submit, please break them up into separate pull requests.
* **Send coherent history**. Make sure each individual commit in your pull request is meaningful. If you had to make multiple intermediate commits while developing, please squash them before submitting.

## Check the code style

If you are having issues with coding standars run

```shell
composer dev:check-style
composer dev:fix-style
```

## Running Tests

The following tests must pass before we will accept a pull request.
If any of these do not pass, it will result in a complete build failure.
Before you can run these, be sure to `composer install` or `composer update`.

```shell
composer dev:build
```