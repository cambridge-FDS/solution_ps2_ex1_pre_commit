# PS2_ex1_pre_commit_hooks

This is the solution to PS2 ex 1: Pre-commit hooks.

## Setup

Install the virtual environment and install your repo from source:

```bash
conda env create -f environment.yml
conda activate gdp
pip install --no-build-isolation -e .
```

To install the pre-commit hooks, run:

```bash
pre-commit install
```

When updating the pre-commit hooks, run:

```bash
pre-commit clean
pre-commit install
```

To run pre-commit hooks on all files, run:

```bash
pre-commit run --all-files
```

to run it on a specific file, run:

```bash
pre-commit run --files <file>
```
