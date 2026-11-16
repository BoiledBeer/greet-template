# Contributing to {{ cookiecutter.package_distribution_name }}

## Set up for development

Activate a virtual environment, then install the package in editable mode:

    python -m pip install -e .

## Run the tests

    python -c "from {{ cookiecutter.package_import_name }} import greet; print(greet('Hee'))"

Expected output: `Hello, Hee!`

## Send a change

1. Create a branch from `main`: `git switch -c <branch>`
2. Commit your change: `git commit -m "<message>"`
3. Push the branch: `git push -u origin <branch>`
4. Open a pull request from your branch to `main`.
