# K-means Clustering on 2D Data (2 Clusters)

This project demonstrates the K-means clustering algorithm on synthetic 2D data using Python and Matplotlib. It includes step-by-step visualizations of the clustering process.

## Features

- Generate synthetic 2D data with 2 clusters
- Randomly initialize centroids
- Assign data points to the nearest centroid
- Update centroids iteratively
- Visualize:
  - Cluster assignments
  - Centroid movements
  - Data points that changed their cluster assignment
- Fixed axis scaling across plots
- Pauses added between iterations for easier observation during teaching

## Requirements

- numpy
- matplotlib
- scikit-learn

Install with:

```bash
pip install numpy matplotlib scikit-learn
```

## How to Run

Open the notebook in Jupyter or Google Colab and run all cells in sequence. Each step of the clustering process will be displayed with visual explanations.

## Note

The iteration loop in Step 6 uses `time.sleep(2)` to pause between frames. Adjust the duration as needed.
