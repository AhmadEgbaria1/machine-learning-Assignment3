# machine-learning-Assignment3
## Description

This project focuses on various machine learning concepts including Nonlinear SVM, Multiclass Classification, PCA, LDA, and KNN. It involves implementing different classifiers, performing dimensionality reduction, and analyzing model performance on different datasets, such as a 2D binary classification dataset, a multiclass separable dataset, the Wine Quality dataset, and the Smiling-Face dataset.

## Table of Contents

- [Project Title](#project-title)
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Datasets](#datasets)
- [Key Concepts Explored](#key-concepts-explored)
- [Results and Discussion](#results-and-discussion)
- [Contributors](#contributors)
- [License](#license)

## Installation

To run this notebook, you will need to have Python and Jupyter (or Google Colab) installed. The required libraries can be installed using pip:

```bash
pip install numpy matplotlib scikit-learn pandas requests opencv-python
If running in Google Colab, some dependencies like kaggle might need to be installed directly within the notebook, as shown in the provided code cells.

Usage
Clone the repository:
git clone <repository-url>
cd <repository-name>
Open the .ipynb notebook file in Jupyter Lab/Notebook or Google Colab.
Run all cells in the notebook sequentially.
Note: For the Kaggle dataset download, you will need to upload your kaggle.json API token as instructed in the notebook.

Datasets
2D Binary Classification Data: Loaded from https://sharon.srworkspace.com/ml/datasets/hw2/svm_data_2d.npy.
Multiclass Separable Data: Generated using sklearn.datasets.make_blobs.
Wine Quality (Red) Dataset: Loaded from https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv.
Smiling-Face Dataset: Downloaded from Kaggle (chazzer/smiling-or-not-face-data). This dataset contains images of smiling and non-smiling faces.
Key Concepts Explored
Nonlinear SVM: Using kernel tricks (Polynomial, RBF) and custom feature mapping (ellipsoid) to classify non-linearly separable data.
Multiclass Classification: Implementation of a One-vs-One (OvO) classifier.
Dimensionality Reduction:
Principal Component Analysis (PCA): Custom implementation and application for image data, including eigenvalue analysis.
Linear Discriminant Analysis (LDA): Application for class-aware dimensionality reduction.
Combined PCA + LDA: Exploring the benefits of sequential application.
K-Nearest Neighbors (KNN): Implementation and tuning with various distance metrics (Euclidean, Manhattan, Cosine, Mahalanobis).
Results and Discussion
The notebook includes detailed analysis and visualizations for each section, discussing:

Hyperplane equations for custom mapped features.
Comparison of different SVM kernels (ellipsoid, poly, rbf) and their generalization performance.
Tuning gamma for RBF kernel to optimize accuracy and understand overfitting/underfitting.
Performance of custom One-vs-One SVM on synthetic multiclass data.
Impact of the C parameter in Linear SVM on the Wine Quality dataset.
Visualization of PCA's effect on image compression and reconstruction.
Optimal number of components for PCA based on explained variance.
Tuning k for KNN classifier using cross-validation on PCA-reduced data.
Comparison of PCA, LDA, and PCA+LDA for dimensionality reduction in image classification.
Comparison of different distance metrics (Euclidean, Manhattan, Cosine, Mahalanobis) for KNN and their impact on accuracy.
Contributors
Ahmad Egbaria (212352504)
Sham abo shtya (322857574)
License
This project is licensed under the MIT License - see the LICENSE file for details. (Assuming an MIT license; please update as needed.) ```
