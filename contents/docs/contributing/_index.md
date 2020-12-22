---
title: How to Contribute
description: Contributing to NewBridge Network
weight: 10
---

# Contributing

We’re still working out the kinks to make contributing to this project as easy and transparent as possible, but we’re not quite there yet. Hopefully this document makes the process for contributing clear and answers some questions that you may have.

## Repository Organization

- NewBrige Network Website

## Branch Organization for Website

Submit all changes directly to the `main branch`. We don’t use separate branches for development or for upcoming releases. We do our best to keep `main` in good shape, with all tests passing. Any accepted changes in `main` will be automatically tested and deployed once the tests are passed.

Code that lands in `main` must be compatible with the latest stable release. It may contain additional features, but no breaking changes. We should be able to release a new minor version from the tip of `main` at any time.

## Bugs

### Where to Find Known Issues

We are using GitHub Issues for our public bugs. We keep a close eye on this and try to make it clear when we have an internal fix in progress. Before filing a new task, try to make sure your problem doesn’t already exist.

### Reporting New Issues

The best way to get your bug fixed is to provide a reduced test case.

## Contribution to Contents

We are accepting documentation contributions to contents. As well as translations to this website.

## Contributor License Agreement (CLA)

In order to accept your pull request, we need you to submit a CLA.

Once you open a pull request, the CLA Bot will check if you have previously signed a CLA to the repo you are contributing to. If not, please follow the CLA Bot's message to finish signing CLA. For each repo, you have only sign the CLA once.

## Style Guide

We use an automatic code formatter called Prettier.

Currently we have a markdown check for the `contents` dirs.

Use following command to check your format for the contents:

```bash
yarn check-contents
```

To auto fix errors or formating, use the command below, this should make your contents looks much better.

```bash
yarn format-contents
```

## License

By contributing to NewBridge Network Website, you agree that your contributions will be licensed under its [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) and [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

See [README on Github](https://github.com/newtonproject/newbridge.network#license) for more information.
