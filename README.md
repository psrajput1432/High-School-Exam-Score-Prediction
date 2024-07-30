# High-School-Exam-Score-Prediction
A project focused on predicting high school students' exam scores based on their demographic information and test scores.
The dataset includes various features such as gender, parental education level, lunch type, and scores from practicals and viva-voce tests.

## Project Details:
### Data Source:
Data is colleted from the high school students in US.
### Task:
Predict the exam score for students based on provided features using machine learning models.
### Dataset:
The project uses train.csv for training and test.csv for making predictions.\
### Models used:
Linear Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost, LightGBM, Support Vector Regression (SVR)
#### Best model - Gradient Boosting Regressor with hyperparameter tuning.
### Evaluation Metrics:
RMSE, MAE, MSE, and R² Score

### Key Steps:
Data Loading and Exploration: Loading datasets and checking for missing values.
Data Preprocessing: Renaming columns, encoding categorical variables, and scaling features.
Model Training and Validation: Evaluating multiple models using cross-validation and selecting the best model based on validation RMSE.
Hyperparameter Tuning: Fine-tuning the best model to improve performance.
Model Evaluation and Interpretation: Assessing the model’s performance with various metrics and visualizing results.
Detailed Data Analysis: Performing exploratory data analysis to understand feature distributions and correlations.
Final Predictions: Making predictions on the test set and preparing a submission file.

#### Files:
train.csv: Training dataset
test.csv: Test dataset
submission.csv: Predicted exam scores for the test dataset
project_code.ipynb: Jupyter notebook with code and results
