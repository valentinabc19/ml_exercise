# Machine Learning Exercise

## Overview

This project involves building and evaluating machine learning models to predict product conditions (e.g., "new" or "used") based on various features. The workflow includes:
1. Exploratory Data Analysis (EDA) to clean and preprocess the dataset.
2. Training multiple machine learning models.
3. Evaluating the models using metrics such as Precision, Recall, F1-Score, and Accuracy.

## Metrics

The following table summarizes the performance of the models:

| Model                  | Precision | Recall  | F1-Score | Accuracy |
|------------------------|----------:|--------:|---------:|---------:|
| Logistic Regression    |  0.782686 | 0.73030 | 0.710491 |  0.73030 |
| Decision Tree          |  0.825589 | 0.81810 | 0.818157 |  0.81810 |
| Random Forest          |  0.827197 | 0.82230 | 0.822479 |  0.82230 |
| K-Nearest Neighbors    |  0.796493 | 0.79665 | 0.796346 |  0.79665 |

## Conclusions

1. **Best Performing Model**:
   - The **Random Forest** model achieved the highest performance across all metrics, with an F1-Score of **0.822479** and an Accuracy of **0.82230**. This makes it the most reliable model for predicting product conditions in this dataset.

2. **Decision Tree**:
   - The **Decision Tree** model performed slightly worse than Random Forest but still achieved strong results, with an F1-Score of **0.818157**. It is a simpler model and may be preferred if interpretability is a priority.

3. **Logistic Regression**:
   - The **Logistic Regression** model had the lowest performance, with an F1-Score of **0.710491**. This suggests that the relationship between features and the target variable may not be entirely linear.

4. **K-Nearest Neighbors (KNN)**:
   - The **KNN** model performed moderately well, with an F1-Score of **0.796346**. However, it may be computationally expensive for larger datasets due to its reliance on distance calculations.