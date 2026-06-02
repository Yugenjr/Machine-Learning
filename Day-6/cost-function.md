# Cost Function

A cost function (loss function) measures how well a model's predictions match the true targets.

- Purpose: quantify error so optimization can reduce it.
- Common types: mean squared error (MSE), mean absolute error (MAE), cross-entropy (log loss).

MSE: average squared difference, sensitive to outliers; used for regression.

MAE: average absolute difference, more robust to outliers.

Cross-entropy: measures dissimilarity between probability distributions; standard for classification.

Optimization: training minimizes the cost via gradients (e.g., gradient descent).

Properties to consider: convexity, differentiability, scale, and sensitivity to outliers.

Regularization: add penalty terms (L1/L2) to the cost to prevent overfitting.

Practical tips: choose loss aligned with task and metrics; monitor training vs validation loss.

Further reading: derivatives, numerical stability, and custom loss functions for specialized tasks.

