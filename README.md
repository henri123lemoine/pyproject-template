# Python Project Template

A minimal Python project template with logging and testing setup. Made for personal use.

## Features

- Logging with loguru
- Environment variables with python-dotenv
- Testing with pytest
- Linting with ruff

## Getting Started

This project uses `uv`. Installation instructions [here](https://docs.astral.sh/uv/getting-started/installation/).

1. Clone the repository
   ```bash
    git clone https://github.com/your-username/repo-name.git
    cd repo-name
    ```

2. Run the project! This should take care of installing dependencies, setting up the virtual environment, and running the project.
   ```bash
   uv run [file path]
   ```

## Development

To install development dependencies, run `uv pip install -r pyproject.toml --all-extras`.

To run tests, use `uv run pytest`.
