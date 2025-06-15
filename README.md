# **Drug Classification Using KNN and Multiclass Logistic Regression**
#### This machine learning project utilizes the K-Nearest Neighbors Algorithm and Multiclass Logistic Regression to predict drugs for patients based on features such as age, sex, blood pressure and cholesterol thresholds, as well as sodium and potassium levels. 
## Tech Stack
#### Python 3.8+: Core programming language for building the project.
#### pandas: For data manipulation and analysis.
#### scikit-learn: Machine learning library used for feature extraction and building classifiers.
#### Logistic Regression and K-nearest Neighbors: Machine learning algorithms used for classification.
## Project Structure
#### 1) Exploratory Data Analysis: Plotting histograms to determine the distribution of each feature and scatter plot of continuous features for each drug type to check for clustering of features and suitability of implementing KNN.
#### 2) Encoding: Applying ordinal encoding for ordinal features like blood pressure and cholesterol thresholds and label encoding for categorical features.
#### 3) Scaling: Separately scaling training and testing data using RobustScaler to minimize the impact of outliers
#### 4) Fitting and Evaluating Logistic Regression Model: This model has a score of 0.91875 on the train data and 0.875 on the test data
#### 5) Optimizing K-Value: Plotting error rate vs K-Value shows that the error rate initially rises, then drastically falls and again increases, forming a U-shaped curve, and we select the minimum error-rate K-Value (n = 18)
#### 6) Fitting and Evaluating K-Nearest Neighbors Algorithm: This model has a score of 0.8 on train data and 0.825 on test data
## Evaluation Metrics
#### Accuracy: Measures the percentage of correct predictions.
#### Precision: Measures the correctness of positive predictions.
#### Recall: Measures how well the model identifies positive instances.
#### F1-Score: Harmonic mean of precision and recall for better evaluation in imbalanced datasets.
## Benefits
#### Automated Analysis: Automates the analysis of large volumes of medical diagnostic data and identifies patterns for drug classification. 
#### Improved Decision-Making: Helps determine the drug required based on the similarity of the patient's biomedical factors with previous cases.
## Contact
#### Author: Souradeep Bhattacharya
#### Email: souradeepbhattacharya11c@gmail.com
