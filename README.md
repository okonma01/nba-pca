# 🏀 NBA Shooting Clusters - PCA Analysis

This project explores NBA player shooting tendencies using Principal Component Analysis (PCA) and clustering techniques. By reducing high-dimensional shooting data into an interpretable 2D space, we uncover patterns in player shot selection and efficiency.

**📌 Live Demo**: [Launch on Binder](https://www.github.com/okonma01/nba-pca)

---

## Project Overview

- Aggregates NBA player shooting stats by season
- Incorporates Per 36 Minutes data to account for shot volume
- Applies PCA for dimensionality reduction
- Implements interactive scatter plots for player insights

---

## Setup & Installation

1. **Clone the repo**:
```
git clone https://github.com/okonma01/nba-pca.git
cd nba-pca
```

2. **Install dependencies**:
```
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook**:
```
jupyter notebook
```

---

## Key Findings

- Distinct player shooting archetypes emerged (spot up shooters, mid-range specialists, iso scorers).
- PCA successfully approximates high-dimensional data while retaining key shot profile information.
Visualizing plot helps in comparing players with similar shot tendencies.

---

## Next Steps

- Experiment with t-SNE or UMAP for alternative dimensionality reduction.
- Use hierarchical clustering for deeper analysis.
- Extend analysis to include playmaking, defense, or overall scoring efficiency.

---

**Author**: Daniel Okonma

**Data Source**: [NBA Stats (1947 - present)](https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats)
