A collection of Jupyter notebooks covering core machine learning algorithms, implemented as part of coursework in Data Science.

Notebooks
1. GradientDescent.ipynb
Implements gradient descent optimization from scratch. Covers learning rate selection, convergence behaviour, and comparison with analytical solutions. Includes experiments on ill-conditioned matrices and step-size sensitivity.
2. LeastSquarevsGradientDescent.ipynb
Compares two approaches to solving linear regression: the closed-form least squares solution (via pseudoinverse) and iterative gradient descent. Highlights trade-offs in computational cost and numerical stability.
3. Regression.ipynb
Explores linear and polynomial regression models. Covers model fitting, overfitting, regularization (L1/L2), and evaluation metrics such as MSE and R².
4. Kernel Functions, kmeans and RBF networks.ipynb
Three topics in one notebook:

Kernel Functions — implements linear, polynomial, RBF, and sigmoid kernels for use in SVMs and kernel-based methods.
K-Means Clustering — Lloyd's algorithm implementation with centroid initialization, convergence tracking, and cluster visualization.
RBF Networks — implements a Radial Basis Function neural network with fit(), decision_function(), and predict() methods.

5. SVD for eigenfaces.ipynb
Implements the Eigenfaces method using Singular Value Decomposition (SVD). Covers fit(), rank_k_approximation(), cumulative_explained_variance(), and reconstruction_error() for dimensionality reduction and face recognition.
6. AdaBoost.ipynb
Implements the AdaBoost ensemble algorithm. Covers weak learner training, sample weight updates across rounds, and final weighted majority voting. Includes comparison with baseline classifiers.
7. RandomForest.ipynb
Implements Random Forest using bagging and random feature subsets. Explores the effect of number of trees, max depth, and feature selection on model accuracy and variance reduction.
8. CrossValidator.ipynb
Implements k-fold and stratified cross-validation from scratch. Used to evaluate model generalization, tune hyperparameters, and plot learning curves.
