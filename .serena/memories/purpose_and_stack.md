# Purpose and tech stack

## Purpose
Python SDK for integrating Paddle Billing with Python applications. Package: `paddle-python-sdk` (PyPI). Use `from paddle_billing import Client` to authenticate and call Paddle API.

## Tech stack
- **Language**: Python >= 3.11
- **Package**: setuptools, `paddle_billing` module
- **Testing**: pytest, pytest-cov, requests-mock
- **Lint/format**: black (line-length 120 in pyproject.toml), flake8 (setup.cfg), pre-commit

## Structure
- `paddle_billing/` – main package
- `examples/` – usage examples
- `tests/` – pytest tests
- `pyproject.toml`, `setup.py`, `setup.cfg`, `pytest.ini`, `.pre-commit-config.yaml`
