# <div align="center">pj<br>[![skeleton](https://img.shields.io/badge/0.0.2rc–219–g781ce0c-skeleton?label=%F0%9F%92%80%20skeleton-ci/skeleton-python&labelColor=black&color=grey&link=https%3A//github.com/skeleton-ci/skeleton-python)](https://github.com/skeleton-ci/skeleton-python/tree/0.0.2rc-219-g781ce0c) [![Supported Python versions](https://img.shields.io/pypi/pyversions/pj.svg?logo=python&label=Python)](https://pypi.org/project/pj/) [![Package version](https://img.shields.io/pypi/v/pj?label=PyPI)](https://pypi.org/project/pj/)</div>

[![Tests](https://github.com/bswck/pj/actions/workflows/test.yml/badge.svg)](https://github.com/bswck/pj/actions/workflows/test.yml)
[![Coverage](https://coverage-badge.samuelcolvin.workers.dev/bswck/pj.svg)](https://coverage-badge.samuelcolvin.workers.dev/redirect/bswck/pj)
[![Documentation Status](https://readthedocs.org/projects/pj/badge/?version=latest)](https://pj.readthedocs.io/en/latest/?badge=latest)

> [!Warning]
> **Work in Progress**. 🚧
>
> Hit the `👁 Watch` button to know when this project is ready to be tried out!

Set up projects for development quickly.

# Idea
- `pj clone [URL]` → clone and install a Python project
- `pj install` → install a Python project
- `pj env` → display info on the installed environment
- `pj config [OPTION] [del|set [VAL]]` → configure `pyproject.toml`
- `pj test` → run the detected test suite
- `pj lint` → run the detected linting suite
- `pj ci` → `pj lint; pj test`

# Installation
To use this globally as a CLI tool only, simply install it with [pipx](https://github.com/pypa/pipx):

```shell
pipx install pj
```

But you might also simply install it with pip to access the library API:

```shell
pip install pj
```

If you use [Poetry](https://python-poetry.org/), then you might want to run:

```shell
poetry add pj
```

## For Contributors
[![Poetry](https://img.shields.io/endpoint?url=https://python-poetry.org/badge/v0.json)](https://python-poetry.org/)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![Pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)
<!--
This section was generated from skeleton-ci/skeleton-python@0.0.2rc-219-g781ce0c.
Instead of changing this particular file, you might want to alter the template:
https://github.com/skeleton-ci/skeleton-python/tree/0.0.2rc-219-g781ce0c/project/README.md.jinja
-->
> [!Note]
> If you use Windows, it is highly recommended to complete the installation in the way presented below through [WSL2](https://learn.microsoft.com/en-us/windows/wsl/install).
1.  Fork the [pj repository](https://github.com/bswck/pj) on GitHub.

1.  [Install Poetry](https://python-poetry.org/docs/#installation).<br/>
    Poetry is an amazing tool for managing dependencies & virtual environments, building packages and publishing them.
    You might use [pipx](https://github.com/pypa/pipx#readme) to install it globally (recommended):

    ```shell
    pipx install poetry
    ```

    <sub>If you encounter any problems, refer to [the official documentation](https://python-poetry.org/docs/#installation) for the most up-to-date installation instructions.</sub>

    Be sure to have Python 3.8 installed—if you use [pyenv](https://github.com/pyenv/pyenv#readme), simply run:

    ```shell
    pyenv install 3.8
    ```

1.  Clone your fork locally and install dependencies.

    ```shell
    git clone https://github.com/your-username/pj path/to/pj
    cd path/to/pj
    poetry env use $(cat .python-version)
    poetry install
    ```

    Next up, simply activate the virtual environment and install pre-commit hooks:

    ```shell
    poetry shell
    pre-commit install
    ```

For more information on how to contribute, check out [CONTRIBUTING.md](https://github.com/bswck/pj/blob/HEAD/CONTRIBUTING.md).<br/>
Always happy to accept contributions! ❤️

# Legal Info
© Copyright by Bartosz Sławecki ([@bswck](https://github.com/bswck)).
<br />This software is licensed under the terms of [MIT License](https://github.com/bswck/pj/blob/HEAD/LICENSE).
