# uv-template

## Open a new project in VS Code

With uv installed, open the cloned project from its root. [Install uv](https://docs.astral.sh/uv/getting-started/installation/)

```sh
code .
```

Trust the workspace and allow automatic tasks when prompted. The **Sync Python environment** task creates `.venv` using the Python version in `.python-version` and installs the locked dependencies, including `ipykernel`. If automatic tasks are disabled, run **Tasks: Run Task** → **Sync Python environment**.

Install the recommended Python and Jupyter extensions. Once the task finishes, open `analysis/0_clean.ipynb`, choose **Select Kernel** → **Python Environments**, and select the interpreter under `.venv`. If VS Code already has another interpreter selected, run **Python: Select Interpreter** and choose the same interpreter.
