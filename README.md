# Exploring-SVMs
In this notebook, we'll explore several classification scenarios using SVMs, each illustrating different challenges. We will generate synthetic data and keep the feature space two-dimensional to ease visual analysis. The classifications we will explore include:
1. **Linearly Separable Data**: This is the simplest scenario, where a linear decision boundary can perfectly separate the classes without any errors.
2.  **Linear, Non-Separable Data**: Here, we encounter data that cannot be perfectly separated by a linear boundary. We introduce a cost parameter, which imposes a penalty for misclassifications and data points that fall on the margin or within the other side of the boundary. This cost is a critical tuning parameter, allowing us to control the trade-off between decision boundary complexity and the rate of misclassification.
3. **Nonlinear Data**: In this scenario, we apply the kernel trick to demonstrate how SVM can classify data that is inherently non-linear. The kernel trick involves transforming the original data into a higher-dimensional space, where the separation problem can again be treated as linear, simplifying the computation.

**Note**: SVMs have fallen into disuse as some other techniques such as Random forests and XGBoost have proven to outperform them in many different problem setups. However, as mathematician myself I can say they are a "beautiful" item to understand for the so called kernel trick, which connects the classification/regression domain with functional analysis.
   
