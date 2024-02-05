## Predicting Students Performance Based ON Their Exam Marks -- ML Project

In this project, we performed data cleaning, feature engineering, scaling, visualization, and model training on a student performance dataset. Here's a concise summary:

# Data Cleaning:

Imported libraries and loaded the dataset.
Checked for missing values and duplicates (none found).
Created a 'total' column by summing scores.
Calculated 'average' scores by dividing 'total' by 3.

# Data Visualization:

Visualized 'average' score distribution using histograms and KDE.
Compare 'average' scores by gender with a Seaborn histogram.

# Feature Engineering:

Identified numerical and categorical features.
Applied one-hot encoding to categorical features and standard scaling to numerical features.

# Model Training and Evaluation:

Trained various regression models, including Linear, Lasso, Ridge, K-Neighbors, Decision Tree, Random Forest, XGBoost, CatBoost, and AdaBoost.
Evaluated models on training and test sets using MAE, RMSE, and R2 scores.

# Steps for Model Improvement:

Random Forest showed promising results.
Possible improvements include hyperparameter tuning, feature selection, and exploring advanced ensemble techniques like stacking.

In summary, we explored the dataset, prepared it for modelling, trained various regression models, and assessed their performance. To enhance the model, we can fine-tune parameters, select important features, and consider advanced ensemble techniques.
