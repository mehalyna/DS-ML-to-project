# Data Science & Machine Learning: From Theory to Project

This repository contains practical learning materials for a course that takes learners from core data science and machine learning concepts to an end-to-end project workflow. Sessions combine concise explanations with executable Jupyter notebooks, hands-on exercises, validation checks, and reusable project outputs.

## Course materials

The current notebooks build on a shared book-catalogue case study.

Each notebook is designed to run independently where practical, using small deterministic local examples when earlier session data is unavailable. Some exercises generate files under `data/raw/` or `data/processed/` when run; these are learning outputs rather than additional course materials.

## Prerequisites

- Python 3.11 or later
- Basic Python and Git knowledge
- Jupyter Notebook or JupyterLab

The notebooks use common Python data-science libraries such as pandas, NumPy, requests, BeautifulSoup, scikit-learn, and joblib. Install the packages required by the notebook you intend to run in your virtual environment.

## Create and activate a virtual environment

From the repository root, create a virtual environment:

```bash
python -m venv .venv
```

Activate it in PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

On Windows Command Prompt:

```bat
.\.venv\Scripts\activate.bat
```

On macOS or Linux:

```bash
source .venv/bin/activate
```

When the environment is active, install the libraries needed for your session. For example:

```bash
python -m pip install --upgrade pip
python -m pip install jupyter pandas numpy requests beautifulsoup4 scikit-learn joblib
```

Start Jupyter from the repository root:

```bash
jupyter notebook
```

Or use JupyterLab:

```bash
jupyter lab
```

To leave the virtual environment, run:

```bash
deactivate
```

## Working with the notebooks

Open a notebook and run its cells in order. Local examples are intended to be deterministic and offline by default. Any optional network demonstrations are not required to complete the core exercises. Review the notebook's notes on data provenance, responsible access, validation, and train/test leakage before adapting examples to a real project.
