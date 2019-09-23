# Contributing Guide

This project adheres to [The Code Manifesto](http://codemanifesto.com) as its guidelines for contributor interactions.

## How to contribute

This is a collaborative effort. We welcome all contributions submitted as pull requests.

(Contributions on wording & style are also welcome.)

### Bugs

A bug is a demonstrable problem that is caused by the code in the repository. Good bug reports are extremely helpful – thank you!

Please try to be as detailed as possible in your report. Include specific information about the environment – version of PHP, etc, and steps required to reproduce the issue.

### Pull Requests

Good pull requests – patches, improvements, new features – are a fantastic help. Before create a pull request, please follow these instructions:

* The code must follow the [PSR-2 Coding Standard](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md). Run `composer cs-fix` to fix your code before commit.
* Write tests
* Document any change in `README.md` and `CHANGELOG.md`
* One pull request per feature. If you want to do more than one thing, send multiple pull request

### Runing tests

```sh
composer test
```

To get code coverage information execute the following comand:

```sh
composer coverage
```

Then, open the `./coverage/index.html` file in your browser.
