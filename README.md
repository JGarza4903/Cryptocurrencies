# Cryptocurrencies Clustering Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Unsupervised%20Learning-yellow)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple)
![PCA](https://img.shields.io/badge/PCA-Dimensionality%20Reduction-green)

## Quick Snapshot
This project applies unsupervised machine learning techniques to analyze cryptocurrency market data and identify natural groupings based on shared characteristics. Using PCA and K-Means clustering, the analysis explores how cryptocurrencies cluster based on behavior rather than predefined labels.

---

## Objective
Identify patterns and groupings within cryptocurrency data using unsupervised learning. Reduce feature dimensionality with Principal Component Analysis (PCA) and apply K-Means clustering to uncover structure in the dataset.

---

## Dataset Overview
The dataset consists of numerical features describing cryptocurrency market behavior, including price movement and market-related metrics.

Key preprocessing considerations:
- Features vary widely in scale, requiring normalization.
- Many variables are correlated, motivating dimensionality reduction.
- No labeled target variable is present, making this an unsupervised learning problem.

---

## Build Journey

### Phase 1 — Data Preparation
- Loaded cryptocurrency market data into a Pandas DataFrame.
- Removed non-numeric or non-informative fields.
- Standardized features to ensure equal weighting in distance calculations.

---

### Phase 2 — Dimensionality Reduction with PCA
- Applied Principal Component Analysis to reduce feature dimensionality.
- Retained the majority of variance while simplifying the feature space.
- Enabled more efficient and interpretable clustering.

---

### Phase 3 — K-Means Clustering
- Used the elbow method to evaluate appropriate cluster counts.
- Applied K-Means to the PCA-transformed dataset.
- Assigned cluster labels to each cryptocurrency.

---

## Analysis & Interpretation
Clustering revealed distinct groupings of cryptocurrencies based on shared market behavior. These groupings suggest that cryptocurrencies can be categorized by factors such as volatility, market activity, and price movement patterns rather than by name or popularity alone.

This type of analysis can support exploratory research, portfolio segmentation, or further downstream modeling.

## Evidence

![Data Clean](Images/Data_cleaned.png)

---

## Key Takeaways
- Unsupervised learning is effective for discovering structure in unlabeled financial data.
- Feature scaling is critical when using distance-based algorithms like K-Means.
- PCA helps reduce noise and correlation while preserving meaningful variance.
- Clustering provides insight into behavioral similarities without requiring prediction targets.

---

## Next Steps
- Experiment with alternative clustering algorithms (DBSCAN, Hierarchical).
- Evaluate cluster stability over time.
- Incorporate additional market indicators.
- Explore visualization techniques for higher-dimensional interpretations.

---

## About
This repository is part of my technical portfolio, demonstrating applied unsupervised learning techniques and analytical reasoning in data exploration.
