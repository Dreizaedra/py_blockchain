# About

A simple python blockchain, created for the sake of it

# How to

### Commit

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pre-commit install
pre-commit install --hook-type commit-msg
pre-commit install --hook-type pre-push
```

### Run

```bash
python3 main.py
```
