# Machine Learning Notes

A structured machine learning curriculum built as Jupyter notebooks. The lessons move from mathematical foundations and data visualization into preprocessing, feature engineering, supervised learning, unsupervised learning, semi/self/active learning, reinforcement learning foundations, and explainable AI.

## Repository Structure

| Path | Purpose |
|---|---|
| `ML_Learning.ipynb` | Original combined notebook / master learning plan. |
| `modules/` | Module-wise notebooks for focused study. |
| `modules/README.md` | Quick links to every module notebook. |
| `modules/images/` and `modules/visuals/` | Visual assets used by the module notebooks. |
| `Requirements.txt` | Python packages needed to run the notebooks. |

## Module Notebooks

| Module | Topic |
|---|---|
| 01 | Mathematical Foundations & Exploratory Data Analysis |
| 02 | Data Visualization & Graphical Analysis |
| 03 | Data Handling, Integrity, & Preprocessing |
| 04 | Feature Engineering, Extraction, & Dimensionality Reduction |
| 05 | Generalization, Validation, & Regularization |
| 06 | Supervised Learning Algorithms |
| 07 | Unsupervised Learning |
| 08 | Semi-Supervised, Self-Supervised, & Active Learning |
| 09 | Reinforcement Learning Foundations |
| 10 | Explainable AI & Specialized Models |

Open the module index here: [modules/README.md](modules/README.md).

## Setup

Create and activate a project-level virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r Requirements.txt
```

Then start Jupyter or open the notebooks in VS Code / JupyterLab using the `.venv` kernel.

## Notes

- The notebooks are written for step-by-step learning, with definitions, where/why each concept is used, formulas where useful, examples, and result interpretation.
- Local environments, caches, downloaded dataset folders, and secret files are intentionally ignored by Git.
- Some notebooks use built-in scikit-learn datasets or small local CSV files for examples.
