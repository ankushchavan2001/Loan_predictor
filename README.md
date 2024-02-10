# Loan_predictor
Title: Predicting Loan Default Using Machine Learning: An Imbalanced Dataset Approach

Description:
The goal of this project was to develop a machine learning model capable of predicting loan default based on various features extracted from a dataset obtained from Kaggle. The dataset contains information such as borrower's age, income, loan amount, credit score, employment details, marital status, and more. The target variable, 'Default', indicates whether a borrower defaulted on their loan.

Data Preprocessing:
Imbalanced Dataset: Initially, the dataset suffered from class imbalance, with a significantly higher number of non-default cases compared to default cases. To address this issue, oversampling techniques such as SMOTE were applied to create synthetic instances of the minority class.
Encoding Categorical Features: Several columns in the dataset were categorical. To prepare the data for modeling, ordinal encoding, one-hot encoding, and label encoding techniques were employed to convert categorical variables into numerical representations.

Exploratory Data Analysis (EDA):
Outlier Detection: Visualization techniques such as box plots and histograms were used to identify outliers in numerical features. Outliers were assessed for potential impact on model performance and handled appropriately.
Distribution Analysis: Histograms and density plots were utilized to examine the distribution of numerical variables. This step aimed to assess the normality of data distributions, which is crucial for certain machine learning algorithms.

Modeling:
Train-Test Split: The dataset was divided into training and testing sets using stratified sampling to ensure that the class distribution was preserved in both sets.
Feature Scaling: Standardization techniques were applied to scale numerical features to a common range, facilitating convergence and improving model performance.
Algorithm Selection: Various classification algorithms, including logistic regression, decision trees, random forests, and gradient boosting, were trained on the dataset to evaluate their performance in predicting loan defaults.

Model Evaluation: Model performance metrics such as accuracy, precision, recall, and F1-score were computed using cross-validation and evaluated using classification reports. Additionally, ROC curves and AUC scores were utilized to assess the models' discriminatory power.

Conclusion:
Through rigorous preprocessing, exploratory analysis, and modeling, the developed machine learning model demonstrated promising performance in predicting loan defaults. The use of oversampling techniques to address class imbalance, along with appropriate feature encoding and scaling, contributed to the model's effectiveness. Future work may involve fine-tuning model hyperparameters and exploring advanced ensemble techniques to further enhance predictive accuracy and robustness.
