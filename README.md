# ML_models
Polynomial Regression This model fits a non-linear curve to the data by creating higher-order features of distance and time. For our dataset, it captures the wave-like patterns of delays that spike during morning and evening rush hours rather than assuming a simple straight-line trend.

Softmax Regression This is a multi-class classification model that calculates a probability distribution to assign data points to one of several categories. We use it to categorize train trips into three distinct risk levels—on-time, late, or severely delayed—based on the journey's length and departure hour.

Linear Discriminant Analysis (LDA) LDA finds the mathematical axis that best separates different classes by maximizing the distance between their averages. It is used on our train data to draw clear boundaries between punctual and delayed trips, effectively creating a "risk map" for different travel conditions.

Lasso Regression This is a linear regression technique that uses L1 regularization to shrink the weights of less important features, sometimes even to zero. For our dataset, it helps us mathematically identify whether the distance or the time of day is the more significant factor causing train delays.

K-Means Clustering This unsupervised algorithm groups data points into clusters based on their similarity to a central point called a centroid. We use it to automatically group similar train journeys together, identifying natural patterns like "short-distance morning trips" versus "long-distance night travel" without needing pre-labeled delay data.