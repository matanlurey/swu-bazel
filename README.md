# Tools for Star Wars: Unlimited

[![Build and Test](https://github.com/matanlurey/swu-bazel/actions/workflows/bazel.yml/badge.svg)](https://github.com/matanlurey/swu-bazel/actions/workflows/bazel.yml)

Assorted tools for the the trading card game, [Star Wars: Unlimited](https://starwarsunlimited.com/).

## Getting Started

This repository uses [Bazel](https://bazel.build/) for building and testing in
a self-contained environment.

For MacOS or Linux (possibly Windows with WSL), invoke `bazel` from the root:

```sh
./bazel build //...
```

As needed, dependencies will be downloaded and the project will be built.


## Testing

```sh
./bazel test //...
```
