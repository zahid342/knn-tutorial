# K-Means Clustering with Silhouette Analysis

This repository contains a complete tutorial on K-Means clustering, with a focus on evaluating clustering performance using silhouette analysis. The notebook walks through dataset creation, clustering, visualization, and quantitative evaluation.

## Contents

- kmeans_silhouette_analysis_tutorial.ipynb : Main tutorial notebook with code and explanations
- README.md : Project overview and setup instructions
- requirements.txt : Python dependencies for the project
- LICENSE : (Optional) Open-source license file
- tutorial.docx / tutorial.pdf : Final report version for academic submission

## Dataset

The dataset is synthetically generated using `make_blobs()` from scikit-learn. It contains 2 numerical features and 4 natural clusters, designed to clearly demonstrate the K-Means algorithm.

## Learning Objectives

- Understand how K-Means clustering works
- Visualize clusters and centroids
- Apply silhouette analysis to evaluate cluster quality
- Interpret silhouette plots and average scores
- Explore how varying k affects clustering

## How to Run

1. Clone this repository:
```
git clone https://github.com/your-username/kmeans-silhouette-tutorial.git
cd kmeans-silhouette-tutorial
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Launch the notebook:
```
jupyter notebook kmeans_silhouette_analysis_tutorial.ipynb
```

## Acknowledgements

- Scikit-learn library for clustering and evaluation tools
- Matplotlib and Seaborn for visualization
