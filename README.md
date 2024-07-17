**Loan Approval Prediction**
**Project Overview**
Welcome to the Loan Approval Prediction project! This project was undertaken to gain hands-on experience in handling messy datasets, performing exploratory data analysis (EDA), detecting and removing outliers, splitting data manually, and training a K-Nearest Neighbors (KNN) model. The objective is to predict loan approvals effectively using machine learning techniques.

Requirements
Dataset:
Loan Approval Prediction Dataset

Project Steps and Experience
1. Data Cleaning
In this step, I loaded the dataset into a Pandas DataFrame. I identified and handled missing values using strategies such as mean/median imputation and forward/backward fill. I documented my chosen strategies to ensure reproducibility. I corrected data types and standardized formats, and addressed any inconsistent or erroneous data entries to ensure data quality.

2. Exploratory Data Analysis (EDA)
I performed EDA to understand the dataset better. This involved generating descriptive statistics and creating visualizations such as histograms, bar charts, box plots, and correlation matrices. Through this process, I documented key findings and patterns that would guide subsequent steps in the analysis.

3. Outlier Detection and Removal
I detected outliers using methods such as Z-score, IQR, and visualization techniques. I developed a function to handle outliers appropriately, either by removing or capping them. I documented my approach and its impact on the dataset, ensuring transparency in the data preprocessing steps.

4. Manual Data Splitting
I manually split the cleaned dataset into training and testing sets with an 80/20 split. This step was crucial to ensure that the model could be trained effectively and evaluated on unseen data.

5. Model Training
I trained a K-Nearest Neighbors (KNN) model on the training set using manual splitting. Additionally, I implemented cross-validation to train the model again and assess its performance more robustly. This helped in understanding the model’s generalizability.

6. Model Evaluation
I evaluated the KNN model using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. I compared the results from the manual split with those from cross-validation. To illustrate the model performance, I created visualizations like confusion matrices and ROC curves.
