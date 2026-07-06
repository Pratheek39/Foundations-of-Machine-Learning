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

Expected inputs:
- `MNIST_data/`
- `data.csv`

### [A2_AI24BTECH11019.ipynb](A2_AI24BTECH11019.ipynb)
Bayesian regression and classification.

This notebook covers:
- Sequential Bayesian update for regression weights
- MAP curve fitting and posterior predictive distributions
- Bias-variance tradeoff using ridge regression
- Generative models and discriminant functions
- Gaussian Naive Bayes, Linear Discriminant Analysis, and L2-regularized LDA
- Effects of class imbalance and Gaussian noise on classifier performance

### [A4.AI24BTECH11019.ipynb](A4.AI24BTECH11019.ipynb)
Dimensionality reduction and unsupervised learning.

This notebook covers:
- PCA on face images with reconstruction analysis
- K-means clustering with k-means++ initialization
- Gaussian Mixture Models trained with EM
- Comparison of K-means and GMM on multiple datasets

Expected inputs:
- `face_data/train/`
- `face_data/test/`
- `data/dataset_A.csv`
- `data/dataset_B.csv`
- `data/dataset_C.csv`

## Notes

- The notebooks are written to be run interactively in Jupyter.
- Several sections generate plots and compare model behavior visually.
- If you are running the notebooks from a fresh clone, make sure the referenced data folders and CSV files are available in the expected paths.
