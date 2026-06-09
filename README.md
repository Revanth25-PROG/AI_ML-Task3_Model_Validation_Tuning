# Model Validation, Overfitting Control & Hyperparameter Tuning

This project uses the California Housing Dataset to predict house prices using machine learning techniques. The dataset was preprocessed and split into training and testing sets. Feature scaling was applied using StandardScaler.

Three models were trained and evaluated:
- Linear Regression
- Ridge Regression
- Decision Tree Regressor

Overfitting was analyzed by comparing training and testing RMSE values. To obtain more reliable performance estimates, 5-Fold Cross Validation was performed using cross_val_score().

Hyperparameter tuning was carried out using GridSearchCV to find the optimal values for max_depth and min_samples_split in the Decision Tree model.

The models were evaluated using RMSE and R² Score, and their performances were compared to select the best model. The results show how model validation and hyperparameter tuning help improve prediction accuracy and model generalization.
