# uv-template

## Open a new project in VS Code

With uv installed, open the cloned project in VS Code using **File → Open Folder**. Trust the workspace and install the recommended Python and Jupyter extensions. [Install uv](https://docs.astral.sh/uv/getting-started/installation/)

For automatic setup, open the Command Palette and choose **Tasks: Manage Automatic Tasks → Allow Automatic Tasks**. This is a one-time VS Code setting for trusted workspaces. Reopen the folder to start the **Sync Python environment** task. To set up just this folder, choose **Tasks: Run Task → Sync Python environment** instead.

The task creates `.venv` using the Python version in `.python-version` and installs the locked dependencies, including `ipykernel`. Once it finishes, open `analysis/0_clean.ipynb` and select the `.venv` interpreter under **Select Kernel → Python Environments**.
