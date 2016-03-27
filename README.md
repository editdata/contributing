# EditData Contributing Guidelines

Contributions to the EditData project are welcome!

In addition to improving the project by refactoring code and implementing relevant features, this project welcomes the following types of contributions:

- **Ideas**: participate in an issue thread or start your own to have your voice heard.
- **Writing**: contribute your expertise in an area by helping expand the included content.
- **Design**: make improvements to the design of documentation, logo, website, & individual modules.
- **Copy editing**: fix typos, clarify language, and generally improve the quality of the content.
- **Formatting**: help keep content easy to read with consistent formatting.

**Before spending lots of time on something, ask for feedback on your idea first!**

Please search issues and pull requests before adding something new to avoid duplicating efforts and conversations.

## Conduct

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.

## Setup

### System dependencies

This project requires you to have [node.js](http://nodejs.org) and [git](https://git-scm.com) installed on your computer.

### Fork the repository on GitHub

### Clone your fork locally

### Install npm dependencies

Install dependencies with the `npm install` command.

## Testing

Tests are run with `npm test`. Unless you're creating a failing test to increase test coverage or show a problem, please make sure all tests are passing before submitting a pull request.

After installing dependencies with `npm install` please run `npm test` to make sure things are working on your computer. If not, please file an issue!

## Code Style

[![standard][standard-image]][standard-url]

EditData repositories use [`standard`][standard-url] to maintain code style and consistency, and to avoid style arguments. `npm test` runs `standard` so you don't have to!

[standard-image]: https://cdn.rawgit.com/feross/standard/master/badge.svg
[standard-url]: https://github.com/feross/standard

---

# Collaborating Guidelines

Individuals making significant and valuable contributions are made collaborators and given commit access to the project.

## Rules

There are a few basic ground rules for collaborators:

1. **No `--force` pushes** or modifying the Git history in any way.
1. **Non-master branches** ought to be used for ongoing work.
1. **External API changes and significant modifications** ought to be subject to an **internal pull request** to solicit feedback from other collaborators.
1. Internal pull requests to solicit feedback are *encouraged* for any other non-trivial contribution but left to the discretion of the contributor.
1. Contributors should attempt to adhere to the prevailing code style.

## Releases

Declaring formal releases remains the prerogative of the project maintainer.

## Changes to this arrangement

This is an experiment and feedback is welcome! This document may also be subject to pull requests or changes by collaborators where you believe you have something valuable to add or change.


## Credit

This document is based on:

- [ngoldman/contributing](https://github.com/ngoldman/contributing)
- [jden/CONTRIBUTING.md](https://github.com/jden/CONTRIBUTING.md)
- [OPEN Open Source Project](http://openopensource.org/)

## License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/)