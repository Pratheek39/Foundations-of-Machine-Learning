# Foundations of Machine Learning

This workspace contains three Jupyter notebooks covering core machine learning topics through hands-on implementations and experiments.

## Notebooks

### [A1.AI24BTECH11019.ipynb](A1.AI24BTECH11019.ipynb)
Parameter estimation and regression.

This notebook covers:
- Maximum likelihood estimation and MAP estimation on image data
- Sampling from the estimated Gaussian model
- Polynomial regression with gradient descent and the normal equation
- Training/test loss comparison across polynomial degrees

**Inputs:**
- `MNIST_data/` — MNIST image dataset
- `data.csv` — CSV file containing regression dataset

**Outputs:**
- Visualizations of MLE and MAP estimates on image data
- Sampled Gaussian data distributions
- Regression loss plots comparing different polynomial degrees
- Model parameters and predictions

### [A2_AI24BTECH11019.ipynb](A2_AI24BTECH11019.ipynb)
Bayesian regression and classification.

This notebook covers:
- Sequential Bayesian update for regression weights
- MAP curve fitting and posterior predictive distributions
- Bias-variance tradeoff using ridge regression
- Generative models and discriminant functions
- Gaussian Naive Bayes, Linear Discriminant Analysis, and L2-regularized LDA
- Effects of class imbalance and Gaussian noise on classifier performance

**Inputs:**
- Dataset(s) for regression and classification tasks (generated or provided internally)

**Outputs:**
- Posterior distributions for regression weights
- Posterior predictive plots with uncertainty bounds
- Bias-variance tradeoff comparisons across regularization strengths
- Classifier performance metrics (GNB, LDA, L2-LDA)
- Visualizations of decision boundaries
- Analysis plots showing effects of class imbalance and noise

### [A4.AI24BTECH11019.ipynb](A4.AI24BTECH11019.ipynb)
Dimensionality reduction and unsupervised learning.

This notebook covers:
- PCA on face images with reconstruction analysis
- K-means clustering with k-means++ initialization
- Gaussian Mixture Models trained with EM
- Comparison of K-means and GMM on multiple datasets

**Inputs:**
- `face_data/train/` — Face image dataset for training
- `face_data/test/` — Face image dataset for testing
- `data/dataset_A.csv` — Clustering dataset A
- `data/dataset_B.csv` — Clustering dataset B
- `data/dataset_C.csv` — Clustering dataset C

**Outputs:**
- PCA components and reconstructed face images
- Scree plots showing variance explained
- K-means cluster assignments and centroids
- GMM parameters (means, covariances, weights)
- Cluster visualizations on multiple datasets
- Comparison plots of K-means vs. GMM performance

## Notes

- The notebooks are written to be run interactively in Jupyter.
- Several sections generate plots and compare model behavior visually.
- If you are running the notebooks from a fresh clone, make sure the referenced data folders and CSV files are available in the expected paths.
