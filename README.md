# uv-template

## Open a new project in VS Code

After cloning the repository created from this template, run the setup command from the project root. [Install uv](https://docs.astral.sh/uv/getting-started/installation/)

```sh
uv sync --locked && code .
```

`uv sync` creates the local `.venv` using the Python version in `.python-version` and installs the locked dependencies, including `ipykernel`. VS Code uses `.venv` as the default interpreter for the workspace.

In VS Code, install the recommended Python and Jupyter extensions. Open `analysis/0_clean.ipynb`, choose **Select Kernel** → **Python Environments**, and select the interpreter under `.venv`. If VS Code already has another interpreter selected, run **Python: Select Interpreter** and choose the same interpreter.
