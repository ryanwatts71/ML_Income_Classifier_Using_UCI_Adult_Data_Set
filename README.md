# ML_Income_Classifier_Using_UCI_Adult_Data_Set
This project aimed to analyze and model income classification data using statistical and machine learning techniques. The analysis included data preprocessing, feature engineering, and model training to predict whether individuals earn more than $50K annually. Key steps and methods used were as follows:

Preprocessing and Feature Engineering:

Removed irrelevant features to simplify the dataset.
Converted categorical variables (e.g., occupation, gender, marital status) into binary indicators.
Created interaction terms and scaled numerical variables for consistent representation.
Exploratory Data Analysis:

Computed proportions and distributions for high-income earners, private sector workers, and other key demographic groups.
Assessed missing data and addressed it systematically.
Model Training and Evaluation:

Conducted LASSO regression using cross-validation to select the optimal regularization parameter for predictive accuracy.
Trained and tuned Random Forest classifiers with different configurations (100, 200, and 300 trees) using 5-fold cross-validation.
Evaluated model accuracy, kappa statistics, and confusion matrices to compare predictive performance across models.
Model Selection and Performance:

The Random Forest model with 100 trees achieved the highest accuracy (81.7%) on the test dataset.
Detailed analysis of false positives, false negatives, and class proportions helped validate model results.
Key Insights:

Simplifying features and tuning hyperparameters improved model interpretability and predictive power.
Random Forest models demonstrated robust performance, with insights on variable importance aiding deeper understanding of income prediction.
This project showcased the integration of statistical analysis and machine learning to solve a real-world classification problem.
