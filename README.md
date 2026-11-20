# Testing Demo

A small Python project for practising unit testing. It has one function and a set of tests that check its behaviour: typical inputs, edge cases and invalid input.

## What's here

- **The function** (`src/`): a single, focused function with clearly defined inputs and outputs.
- **The tests** (`tests/`): [pytest](https://docs.pytest.org/) tests describing what the function should do, including the cases where it should fail.

## Getting started

Run these from the project folder. Each block can be copied and pasted in one go.

### 1. Create and activate a virtual environment

**macOS / Linux**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

**Windows (PowerShell)**

```powershell
py -m venv .venv
.venv\Scripts\Activate.ps1
```

> If PowerShell says running scripts is disabled, run this once, then activate again:
>
> ```powershell
> Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
> ```

**Windows (Command Prompt)**

```bat
py -m venv .venv
.venv\Scripts\activate.bat
```

Once it's active, you'll see `(.venv)` at the start of your terminal prompt.

### 2. Install pytest

```bash
python -m pip install --upgrade pip pytest
```

### 3. Run the tests

```bash
python -m pytest
```

### Leaving the virtual environment

```bash
deactivate
```

## Why

The tests are written alongside the function, and often before it, so they work as a specification. Reading them should tell you what the function does without opening its code.
