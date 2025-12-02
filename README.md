# Soccer Players Clustering

This project aims to cluster soccer players based on their detailed match statistics using various unsupervised learning algorithms.

## About the Dataset

The dataset used in this project is from Kaggle: [Soccer Detailed Players Match Data](https://www.kaggle.com/datasets/spicemix/soccer-detailed-players-match-data?resource=download&select=players_away_matches.csv). It contains detailed statistics for each player per match for the away team.

## Project Workflow

The project is divided into three main parts, each in its own Jupyter Notebook:

1.  **`EDA/eda.ipynb`**: Exploratory Data Analysis to understand the data distribution, correlations, and initial insights.
2.  **`feature_engineering/feature_engineering.ipynb`**: Preprocessing and feature engineering steps, including:
    *   Handling missing values
    *   Encoding categorical features
    *   Scaling and standardization
    *   Outlier detection
3.  **`final/final.ipynb`**: Application and evaluation of different clustering models.

## Clustering Models

The following clustering algorithms were evaluated:

*   K-Means
*   K-Medoids
*   Agglomerative Clustering
*   DBSCAN
*   Gaussian Mixture Models (GMM)

The models were evaluated using metrics such as the silhouette score, Calinski-Harabasz score, and Davies-Bouldin score.

## Visualization

PCA and t-SNE were used for dimensionality reduction to visualize the resulting clusters in 2D space. The output visualizations are saved in the `final/` directory.

## How to Run

To reproduce the results, run the Jupyter Notebooks in the following order:

1.  `EDA/eda.ipynb`
2.  `feature_engineering/feature_engineering.ipynb`
3.  `final/final.ipynb`

Ensure all the required Python libraries are installed. The main libraries used are pandas, numpy, scikit-learn, matplotlib, and seaborn.
