Short description:
This project implements a multi-method study for analyzing and visualizing football players’ skills using the Football Players Data dataset from Kaggle.
The goal is to compare dimensionality reduction approaches (PCA, Classical MDS, Non-metric MDS) and explore latent patterns in players’ technical, physical, and mental attributes while excluding non-performance features (e.g., personal, economic, or club-related data).

Key facts:
- Dataset: Football Players Data (Kaggle)
- Source: https://www.kaggle.com/datasets/maso0dahmed/football-players-data
- License: Apache License 2.0
- Data: ~18,000 players, 51 attributes
- Focus: On-pitch technical, physical, and mental skills
- Environment: Python (pandas, numpy, scikit-learn, plotly, matplotlib, seaborn, factor_analyzer)

Methods compared:
- Principal Component Analysis (PCA) – linear dimensionality reduction
- Classical Multidimensional Scaling (MDS) – distance-preserving embedding
- Non-metric MDS – non-linear, rank-based dimensionality reduction
- KMO and correlation tests – dataset suitability and feature selection
- Evaluation metrics / insights:
- Explained variance ratio (PCA)
- Stress and dissimilarity metrics (MDS)
- Visual cluster separation (player similarity)
- Interpretability of low-dimensional projections

Usage:
- Run the notebook sequentially without modifying cell order.
- Review the analysis and visualization cells for plots and conclusions.
- Dataset should be placed as fifa_players.csv in the project root directory.

Python version: 3.12