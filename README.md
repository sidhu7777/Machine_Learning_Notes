# Machine Learning, Deep Learning, and Generative AI Notes

A structured learning repository for three connected paths:

1. **Machine Learning** — existing detailed classical ML curriculum.
2. **Deep Learning** — folder prepared; module design will be discussed and built next.
3. **Generative AI** — folder prepared; module design will be discussed and built after Deep Learning planning.

The current completed content is inside `machine_learning/`.

## Repository Structure

| Path | Purpose |
|---|---|
| `machine_learning/` | Existing ML notebooks, datasets, images, visuals, and validation files. |
| `machine_learning/modules/` | Module-wise Machine Learning notebooks. |
| `deep_learning/` | Placeholder folder for the future Deep Learning curriculum. |
| `generative_ai/` | Placeholder folder for the future Generative AI curriculum. |
| `Requirements.txt` | Python packages used by the current notebooks. |

## Current Machine Learning Curriculum

Open the ML module index here: [machine_learning/modules/README.md](machine_learning/modules/README.md).

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

The original combined notebook is here: [machine_learning/ML_Learning.ipynb](machine_learning/ML_Learning.ipynb).

## Setup

Create and activate a project-level virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r Requirements.txt
```

Then open the notebooks in VS Code, JupyterLab, or GitHub.

## Learning Style

The notebooks are written in a student-friendly flow:

```text
definition → where used → why used → intuition → formula → dataset example → code → output meaning → mistakes
```

## Notes

- Local environments, caches, downloaded dataset folders, and secret files are ignored by Git.
- Deep Learning and Generative AI folders are intentionally empty except for their README files until their detailed module structures are finalized.
