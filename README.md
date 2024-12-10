# Python Project Template

This template is meant for personal use and may not be suitable for all projects.

## Usage

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
