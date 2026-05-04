# hello-world (Python)

Minimal Python package created for Linear **TNG-5**.

## Run locally.

From this directory (`hello_world/`):

```bash
python -m hello_world
```

Or after editable install:

```bash
pip install -e .
hello-world
```

Run from the **repository root** (the folder that contains `pyproject.toml`) so `python -m hello_world` resolves the package correctly.

## Tests

```bash
pip install -e ".[dev]"
pytest -q
```

## CI

GitHub Actions runs the same tests on Python 3.10 and 3.12 on every push and pull request to `main` (see `.github/workflows/ci.yml`).

## GitHub

Remote repository: **https://github.com/nochimo/hello-world**

```bash
git clone https://github.com/nochimo/hello-world.git
cd hello-world
python -m hello_world
```

To use this folder as a working clone with `origin` set to that URL:

```bash
git init
git remote add origin https://github.com/nochimo/hello-world.git
git fetch origin
git checkout -b main --track origin/main
```
