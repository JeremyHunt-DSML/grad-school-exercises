# Feature Selection and Dimensionality Reduction

## Overview
This project explores the impact of dimensionality reduction and feature selection on machine learning models, utilizing two distinct datasets. It demonstrates how proper data preparation (like scaling) interacts with techniques like Principal Component Analysis (PCA) and Chi-Squared (χ²) feature selection to optimize model performance and efficiency.

## Key Skills & Technologies Demonstrated
* **Python Libraries:** `pandas`, `numpy`, `scikit-learn`
* **Regression (House Prices):** Linear Regression
* **Classification (Mushroom Dataset):** Decision Trees
* **Dimensionality Reduction:** Principal Component Analysis (PCA)
* **Feature Selection:** Variance Threshold, Chi-Squared (χ²) Selector
* **Data Preprocessing:** StandardScaler, MinMaxScaler

## Part 1: House Prices (Linear Regression & PCA)
This section predicts house prices by comparing four modeling approaches:
1. A baseline model using all available features.
2. A model using PCA to retain 90% of variance (without scaling).
3. A model using PCA with proper feature scaling.
4. A model using only high-variance features after Min-Max scaling.

**Key Takeaway:** The exercise highlights that process without preparation produces nonsense. PCA is highly sensitive to the scale of the features; applying scaling before PCA turned it from a failing model into a highly effective dimensionality reduction tool.

## Part 2: Mushroom Classification (Decision Trees & χ²)
This section builds a classifier to predict whether a mushroom is edible or poisonous based entirely on categorical features. It demonstrates the use of a Chi-Squared (χ²) feature selector to aggressively reduce the feature space, proving that the model can maintain accuracy using only 5 of the original 95 features by isolating the most statistically significant predictors.
