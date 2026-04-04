# Project Setup

This is a [uv](https://docs.astral.sh/uv/) Python project.

- Use `uv run <script>` to run Python scripts (e.g. `uv run main.py`)
- Use `uv add <package>` to add dependencies (updates `pyproject.toml` and `uv.lock`)
- Use `uv sync` to install dependencies from the lockfile
- Never use `pip install` directly; always use `uv`
- The virtualenv is managed by uv at `.venv/`
- Python version is pinned in `.python-version` (currently requires >=3.14)
