# Predicting-Exam-Score
 This project focuses on building predictive models to estimate students' exam scores based on academic and behavioural factors such as attendance, study hours, tutoring sessions, and parental education levels.
 
Project Workflow
1. Problem Definition
Identified Exam Score as the target variable and selected relevant academic and behavioural predictors.

2. Exploratory Data Analysis (EDA)
Descriptive statistics
Correlation heatmaps and distribution plots
Identified missing values and outliers

3. Data Preprocessing
Imputed missing values using mean imputation
Scaled data using MinMaxScaler
Selected features based on correlation and domain relevance

4. Model Building
Trained and evaluated two models:
Linear Regression
Random Forest Regression

5. Model Evaluation
Used performance metrics:
R² Score
RMSE (Root Mean Squared Error)
MAE (Mean Absolute Error)
Performed residual analysis to validate assumptions.

Key Findings
Attendance Rate and Hours Studied emerged as the most important predictors.
Linear Regression slightly outperformed Random Forest in terms of accuracy and residual behaviour.
Random Forest helped capture non-linear patterns and provided valuable feature importance insights.

Conclusion
Regression models can effectively estimate exam scores using accessible student data. Such tools can aid educational institutions in early intervention strategies to improve academic performance.

Future Work
Incorporate more diverse variables (e.g., mental health, socioeconomic status)
Apply advanced models (e.g., Gradient Boosting, Neural Networks)
Build an interactive dashboard for real-time predictions

Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
