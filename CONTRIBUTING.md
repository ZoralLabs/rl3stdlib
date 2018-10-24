
# Contributing to RL3 Standard Library
Contributions are welcome! There are many ways to contribute to this project: reporting bugs and feature requests, spreading the word, and adding new features and patches.

## Getting Started
* Make sure you have a GitHub account.
* Open a [new issue](https://github.com/jokruger/rl3stdlib/issues), assuming one does not already exist.
* Clearly describe the issue including steps to reproduce when it is a bug.

## Making Changes
* Fork this repository.
* Make changes and commit.
* Make sure your commit messages are well formatted.
* If your commit fixes an open issue, reference it in the commit message.
* Run all the tests (if existing) to assure nothing else was accidentally broken.

## Submitting Changes
* Submit a `Pull Request` on a master branch.
* Wait for maintainer feedback.

## Licensing
The RL3 Standard Library is licensed under the Apache License. Anything contributed to RL3 Standard Library must be released under this license.

## Code Style Notes

`UPPER_CASE_NAME` is used for public patterns and predicates.

`CamelCaseName` is used for 'local' patterns and predicates (i.e. defined for internal purposes - can be used by derived programs, but it is not expected).

`_NB` suffix can be used to inform that the pattern is based on 'ignore blanks' matching.

`_WEAK` suffix is used to identify weak patterns.

`_STRONG` suffix is used to identify strong patterns.
