# Suggested commands

- `pip install -e .` or `pip install paddle-python-sdk` – install package
- `pip install -e ".[dev]"` – install with dev deps (pytest, black, flake8, pre-commit)
- `pytest` – run tests (pytest.ini)
- `black .` – format
- `flake8` – lint (respects setup.cfg)
- `pre-commit run --all-files` – run pre-commit hooks
- Use virtualenv/venv for local dev.
