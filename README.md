Credit Card Fraud Detection Project Report
Student Name: Tohid
Batch: 17
University: Bennett University
Team: Individual (Sole team member)

Project Overview
This project aims to detect fraudulent credit card transactions using machine learning, focusing on data preprocessing, visualizations, and the application of Logistic Regression for classification.

Dataset
The creditcard.csv dataset was used, containing features such as Time, Amount, and Class (0 for legitimate, 1 for fraudulent).

Class Distribution: The dataset is highly imbalanced, with most transactions legitimate and only a few fraudulent.
Steps Completed
1. Data Preprocessing
Data Inspection: The dataset was loaded and checked for null values, data types, and the shape of the data.
Class Distribution Analysis: The distribution of legitimate and fraudulent transactions was examined.
2. Data Sampling
Under-Sampling Technique: To balance the dataset, a sample of legitimate transactions matching the number of fraudulent transactions was selected, creating a balanced dataset for training.
3. Feature Scaling
Standardization: Using StandardScaler, features were standardized to ensure uniform contribution across the model.
4. Model Training and Testing
Train-Test Split: The dataset was split into an 80% training set and a 20% test set, stratified to maintain class balance.
Logistic Regression Model: Logistic Regression was chosen for simplicity and interpretability in binary classification tasks, with a maximum iteration setting of 1000.
Model Evaluation: The model’s accuracy was tested on both training and test sets.
5. Visualizations
Additional visualizations include:

Transaction Amount Distribution: Histograms show the distribution of transaction amounts by class.
Class Distribution Plot: A count plot of legitimate vs. fraudulent transactions in the balanced dataset.
Confusion Matrix for Test Set: Visualization of true and false positives and negatives, providing detailed model performance.
Results
Training Accuracy: X% (replace with actual training accuracy)
Testing Accuracy: Y% (replace with actual testing accuracy)
The Logistic Regression model showed effective performance in distinguishing between legitimate and fraudulent transactions on the balanced dataset.

Future Work
Further improvements could include:

Model Comparison: Testing other models such as Random Forest, Support Vector Machines (SVM), or Neural Networks for robustness.
Cross-Validation: Using cross-validation to refine performance estimates.
Hyperparameter Tuning: Adjusting Logistic Regression parameters for potential performance gains.
Feature Engineering: Adding new features or using dimensionality reduction (like PCA) to improve the model’s effectiveness.
