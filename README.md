# my-poetry-project

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)


CLI for generating projects using Python Poetry.

## Developer Installation

Install Python 3.9.4, ideally with `pyenv`. Then, to manage your environment, install Poetry:

```sh
$ curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/install-poetry.py | python -
```

To use autocompletion for Poetry in Zsh, add the following to your `~/.zshrc` file (if not already there):

```sh
fpath+=~/.zfunc
compinit
```

```sh
$ mkdir ~/.zfunc
$ poetry completions zsh > ~/.zfunc/_poetry
$ exec zsh
```

To set up an environment:

```sh
$ poetry shell
```
