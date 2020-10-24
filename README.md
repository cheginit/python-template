# A template for a Python-based project

This template supports the following:

- The code linitng is done using [pre-commit](https://pre-commit.com/) and can be run by issuing `make lint` command. You can add it as a hook to the repository by running `pre-commit install` so whenever you commit a change it will be run automatically. You can check `.pre-commit-config.yml` file to edit configuration.
- Some of the linters such as `flake8` and `isort` can be configured using the `setup.cfg` file as well.
- A Conda environment file, `environment.yml` is available to add all the project dependencies.
- The project license is MIT.
