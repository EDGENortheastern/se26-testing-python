# Testing Demo

A small Python project for practising unit testing. It has one function and a set of tests that check its behaviour: typical inputs, edge cases and invalid input.

## What's here

- **The function** (`src/`): a single, focused function with clearly defined inputs and outputs.
- **The tests** (`tests/`): [pytest](https://docs.pytest.org/) tests describing what the function should do, including the cases where it should fail.

## Getting started

```bash
# create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate

# install pytest
pip install pytest

# run the tests
pytest
```

## Why

The tests are written alongside the function, and often before it, so they work as a specification. Reading them should tell you what the function does without opening its code.
