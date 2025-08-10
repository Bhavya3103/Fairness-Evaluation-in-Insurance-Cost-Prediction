Data Preprocessing: Standardized numerical features, One-hot encoded categorical variables.

Model Training: Implemented Gradient Boosting Regression for cost prediction, Built separate models for smoker and non-smoker groups to capture group-specific patterns.

Fairness Evaluation: Compared Mean Absolute Error (MAE) between smoker and non-smoker predictions to detect bias, Identified performance disparities where one group experienced systematically higher prediction errors.

Fairness Mitigation Techniques:Loss reweighting to balance group-specific errors during training, Post-processing corrections to adjust predictions after model training.

Results: Reduced MAE disparity between smoker and non-smoker groups. Maintained strong overall predictive performance, Improved equity in insurance cost estimates.
