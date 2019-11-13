# Scikit-Learn-Lab---Parameter-Tuning-of-Classification-Models-using-GridSearch

List of Algorithms and Prameters
1. Decision Tree
Parameters: At least four out of the following:
max depth,
min samples split,
min samples leaf,
min weight fraction leaf,
max features,
max leaf nodes,
min impurity decrease
2. Neural Net
Parameters: At least four out of the following:
hidden layer sizes,
activation,
alpha,
learning rate,
max iter,
tol,
momentum,
early stopping
3. Support Vector Machine
Parameters: At least four out of the following:
C (Error Penalty),
kernel and associated parameters i.e. if you choose polynomial kernel, you need to vary degree
or if you choose rbf kernel, you need to vary gamma
max iter,
random state
4. Gaussian Naive Bayes
Parameters Only one parameter available:
priors
5. Logistic Regression
Parameters: At least four out of the following:
penalty,
tol,
C (inverse of regularization strength),
_t intercept,
class weight,
max iter,
multi class
6. k-Nearest Neighbors
Parameters: At least four out of the following:
n neighbors,
weights,
algorithm,
p (power parameter for the Minkowski metric)
7. Bagging
Parameters: At least four out of the following:
n estimators,
max samples,
max features,
random state
8. Random Forest
Parameters: At least four out of the following:
n estimators,
criterion,
max depth,
max features,
min samples split,
min samples leaf
9. AdaBoost Classi_er
Parameters: At least four out of the following:
n estimators,
learning rate,
algorithm,
random state
10. Gradient Boosting Classi_er
Parameters: At least four out of the following:
loss,
learning rate,
n estimators,
max depth,
min samples split,
min samples leaf,
max features,
min impurity decrease
11. XGBoost
If the above link doesn't provide you with the full details, consult this one -
https://xgboost.readthedocs.io/en/latest/python/python_api.html#module-xgboost.sklearn
Parameters: At least four out of the following:
learning rate,
n estimators,
min child weight,
max delta step,
booster,
seed
