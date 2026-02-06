# PCA-Dimensionality-Reduction-Task13
Implementation of Principal Component Analysis (PCA) on MNIST dataset to study dimensionality reduction, explained variance, and its impact on classification accuracy using Logistic Regression.
# Task 13: PCA – Dimensionality Reduction
## Objective
To understand dimensionality reduction using Principal Component Analysis (PCA) and analyze the trade-off between variance retention and model performance.

## Dataset
- MNIST handwritten digits dataset (28x28 images flattened to 784 features)

## Steps Performed
1. Loaded MNIST dataset and flattened images into feature vectors.
2. Standardized features using StandardScaler.
3. Applied PCA with 2, 10, 30, and 50 components.
4. Analyzed explained variance ratio.
5. Plotted cumulative explained variance curve.
6. Reduced dataset using PCA.
7. Trained Logistic Regression on:
   - Original data
   - PCA reduced data (30 components)
8. Compared accuracy before and after PCA.
9. Visualized 2D PCA scatter plot.

## Results
- PCA helped reduce dimensionality significantly while retaining most variance.
- Slight drop in accuracy observed after dimensionality reduction.
- 2D visualization shows class separation trends.

## Files in Repository
- PCA_MNIST_Task13.ipynb → Python notebook
- pca_variance_curve.png → Explained variance plot
- pca_2d_scatter.png → PCA 2D visualization
- accuracy_comparison.png → Accuracy comparison
