**Lasso and Ridge Regularization**

An overfitted model cannot recognize the unseen data and will fail on given some new Inputs.

What is Variance?

Variance tells us about the spread of the data points. It calculates how much a data point differs from its mean value and how far it is from the other points in the dataset.

What is Bias?

It is the difference between the average prediction and the target value.

\*\*Low bias and low variance will give a balanced model, whereas high bias leads to underfitting, and high variance lead to overfitting.

**Low Bias:** The average prediction is very close to the target value

**High Bias:** The predictions differ too much from the actual value

**Low Variance:** The data points are compact and do not vary much from their mean value

**High Variance:** Scattered data points with huge variations from the mean value and other data points.

So! To make a good fit, we need to have a correct balance of bias and variance.

**What is Regularization?**

Regularization is one of the ways to improve our model to work on unseen data by ignoring the less important features.

It minimizes the validation loss and tries to improve the accuracy of the model.

It avoids overfitting by adding a penalty to the model with high variance, thereby shrinking the beta coefficients to zero.

We have two types of regularization:

A.     **Lasso** regularization

B.     **Ridge** regularization

**What is Lasso Regularization (L1)?**

* *   It stands for Least Absolute Shrinkage and Selection Operator
* *   It adds L1 the penalty
* *   L1 is the sum of the absolute value of the beta coefficients

**Cost function = Loss + λ + Σ ||w||**

Where,

Loss = sum of squared residual

λ = penalty

w = slope of the curve

**What is Ridge Regularization (L2)**

* *   It adds L2 as the penalty
* *   L2 is the sum of the square of the magnitude of beta coefficients

**Cost function = Loss + λ + Σ ||w||2**

Where,

Loss = sum of squared residual

λ = penalty

w = slope of the curve

\* λ is the penalty term for the model. As λ increases cost function increases, the coefficient of the equation decreases and leads to shrinkage.
