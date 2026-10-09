# ML_G84_G2_P2 — Clustering (Machine Learning, Practice 2)

Second practical assignment for the Machine Learning course (group G84, team G2). The project explores unsupervised learning with **clustering algorithms**, applying them to real and synthetic datasets and comparing the results.

The assignment statement is in [`Practica2_clustering.pdf`](Practica2_clustering.pdf).

## Repository contents

| File | Description |
|------|-------------|
| `Practica2_clustering.pdf` | Assignment statement and requirements |
| `segunda_practica.ipynb` | Main notebook with the analysis, experiments and conclusions (created in Google Colab) |
| `notebook.ipynb` | Working/earlier notebook |
| `tutorial.ipynb` | Tutorial notebook used as a reference for the techniques applied |
| `semillas.csv` | Seeds dataset used for the clustering experiments |
| `DBSCAN.csv` | Dataset used to study density-based clustering (DBSCAN) |
| `.gitignore` | Git ignore rules |

## Methods

- **DBSCAN** (density-based clustering), using `DBSCAN.csv`
- Additional clustering experiments on the seeds data (`semillas.csv`)

<!-- Add or remove algorithms here to match what the notebook covers (e.g. K-Means, hierarchical/agglomerative, Gaussian Mixtures) -->

## Getting started

### Requirements

- Python 3.9+
- Jupyter Notebook / JupyterLab, or Google Colab
- `numpy`, `pandas`, `matplotlib`, `scikit-learn`

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

### Running the notebooks

```bash
git clone https://github.com/iborgstedt2848/ML_G84_G2_P2.git
cd ML_G84_G2_P2
jupyter notebook segunda_practica.ipynb
```

Or open `segunda_practica.ipynb` directly in [Google Colab](https://colab.research.google.com/) and upload `semillas.csv` and `DBSCAN.csv` to the session.

Run the cells from top to bottom; the CSV files are expected to be in the same folder as the notebook.

## Results

Results, plots, and discussion are in `segunda_practica.ipynb`.

## Authors

Group G2 — Machine Learning, group G84.
Isabelle Borgstedt

<!-- Add team member names here -->
