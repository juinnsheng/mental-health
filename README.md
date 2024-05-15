# Mental Health Detection Application for Healthcare Workers

According to a National Mental Health Survey of Doctors and Medical Students 2013, doctors are reported to have higher rates of psychological distress and attempted suicide compared to the general population. The levels of stress experienced by KKM doctors are so high that there are reported cases of suicide among doctors in Malaysia.

1. Data Collection
I have conclusively decided on this dataset (https://www.kaggle.com/datasets/thedevastator/medical-student-mental-health). 

2. Data Cleaning
Since the data is collected from a survey, there can be potential duplicated data or incorrectly filled data which we have clean. We have also checked for outliers and carried out feature engineering techniques to create the target variables.

3. EDA
Correlation analysis, pair plots, pie charts, bar charts, heatmaps, histograms, and ANOVA analysis is conducted using the dataset

4. Data Modelling
Since this is a classification problem, I have used algorithms like DecisionTree, Logistic Regression, K-Nearest Neighbours, and XGboost. We plan to split the dataset to 80/20
using Scikit-Learn train-test-split. SMOTE-ENN is used to address class imbalance and RandomizedSearchCV is used to find the best parameters for each of the model

5. Deployment
The best model is then deployed via Streamlit
