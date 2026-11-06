# Data Science Projects

This repository contains a collection of Data Science projects implemented mostly in Python as part of university coursework.

## Course information

The coursework involves handling real-world tabular and economic datasets with modern tools to extract useful information about a given dataset. This means that any project involving data analysis will involve uncovering properties, finding patterns and manipulating data in a way that will provide pure actionable information **without** any interpretation of the results gathered along the way, as this is subjective and lies beyond the scope of this DS-focused course.

### Projects Directory

| № | Directory | Topic | Tools & techniques |
|---|---|---|---|
| 1 | `preliminary-and-correlation-analysis/` | Data Cleaning & Statistical Screening | Hampel Filter tuning, Shapiro-Wilk / KS / χ² normality tests, Spearman correlation, Collinearity screening |
| 2 | `factor-analysis-and-dimensionality-reduction/` | Factor Analysis & Manifold Learning | Bartlett sphericity & KMO tests, PCA, Varimax & Quartimax rotations, Creditworthiness index, KernelPCA, Isomap, UMAP, t-SNE, Trustworthiness validation |

---

## Tech Stack

- **Language**: Python 3.14+
- **Environment & dependency manager**: [`uv`](https://github.com/astral-sh/uv)
- **Development environment**: JetBrains PyCharm 2026.2.4

---

## Setup & Execution

- Ensure you have Python and `uv` installed. If you don't have `uv`, install it via:
```bash
# For Windows:
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

# For macOS and Linux:
curl -LsSf https://astral.sh/uv/install.sh | sh
```

- Clone the repository and install dependencies using `uv`:
```bash
uv sync
```

- Launch your preferred Jupyter environment:
```bash
uv run jupyter lab
```

- Navigate to the desired project folder and run the corresponding `.ipynb` file:
```bash
uv run jupyter notebook [filename].ipynb
```

*Note: Notebooks contain pre-rendered figures and evaluation metrics for direct previewing on GitHub.*