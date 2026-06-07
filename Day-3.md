---
---

--- Before Day-3 ---
I already knew how to create standard Python virtual environments and use pip.
--- 

## Day-3 Checklist

- [x] I can run a Python script using `uv run script.py` without setting up a local virtual environment
- [x] I know where the temporary virtual environment is created when running the `uv add --script script.py pandas` command followed by `uv run script.py`
- [x] I can create a new Python project using `uv init` and understand what `pyproject.toml` is used for
- [x] I can add a dependency (e.g., `requests`) using `uv add` and see it reflected in the lockfile
- [x] I can create a traditional virtual environment using `uv venv` and know when to use it
- [x] I understand why installing packages globally with `pip install` is a bad habit
- [x] I can open a project in VS Code, select the correct Python interpreter, and run code from the integrated terminal
- [x] I know the difference between a `.py` script and a `.ipynb` notebook, and when to use each

--- After Day-3 ---
I learned these things as well, apart from the checklist:
- How `uv` manages temporary script environments inline using PEP 723 metadata.
- Setting up workspaces using `pyproject.toml` and managing lockfiles.
---

--- Feedback (Suggestions for the TDS Team) ---
Excellent overview of the modern Python package manager `uv` and why it is superior to legacy setups.
---

---
---
