# Credit-card-Risk-Assessment
This project utilizes machine learning techniques to assess credit card risk based on individual demographic, financial, and loan details. By analyzing the dataset, the goal is to predict whether an individual is likely to default on a loan, providing valuable insights for risk assessment in the credit industry.

Methods:

Data Cleansing: The dataset is checked for missing values, and any missing values are handled appropriately.
Data Preprocessing: Categorical variables are encoded using one-hot encoding, and numerical features are scaled using StandardScaler.
Exploratory Data Analysis (EDA): The distribution of each feature is explored through histograms, and correlations between features and the target variable are analyzed using a correlation heatmap.
Model Development: A Random Forest classifier is trained on the preprocessed data to predict loan status.
Model Evaluation: The accuracy of the trained model is evaluated on both training and testing datasets. A confusion matrix and classification report are generated to assess model performance.
Results: The results of the analysis, including training accuracy, testing accuracy, and the confusion matrix, are summarized. Additionally, the distribution of loan status and the Receiver Operating Characteristic (ROC) curve are visualized to provide further insights into model performance.
Results:

Training Accuracy: [Training Accuracy]
Testing Accuracy: [Testing Accuracy]
Confusion Matrix: [Confusion Matrix]
Visualizations:

Histograms of feature distributions
Correlation Heatmap
Confusion Matrix
Distribution of Loan Status
Receiver Operating Characteristic (ROC) Curve
Files:

credit_risk_dataset.csv: Dataset containing credit card risk assessment data.
credit_card_risk_assessment.py: Python script for data analysis and model development.
Dependencies:

pandas
numpy
matplotlib
seaborn
scikit-learn
