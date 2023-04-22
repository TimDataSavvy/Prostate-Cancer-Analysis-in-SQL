Prostate Cancer Analysis with SQL
This repository contains the code and results of an analysis of a prostate cancer dataset using SQL.

Project Overview
The goal of this project is to analyze a dataset of prostate cancer diagnoses and provide insights into factors that contribute to malignancy. The dataset contains information on patient id, diagnosis result (malignant or benign), and various features such as radius, texture, perimeter, area, smoothness, compactness, symmetry, and fractal dimension. The project uses SQL to perform data cleaning and exploratory data analysis.

Technologies
The project is primarily implemented using SQL Server Management Studio, which provides a comprehensive set of tools for working with databases and SQL queries. Other technologies used include Excel for data cleaning and visualization, and GitHub for version control and project management.

Dataset
The dataset used for this analysis is the "Prostate Cancer" dataset from the UCI Machine Learning Repository. The dataset contains 569 observations and 10 features. The data was collected by the University of Wisconsin Hospitals, Madison from patients who were undergoing biopsy for suspected prostate cancer.

Analysis Steps
The following steps were taken to analyze the dataset:

Data cleaning: The dataset was cleaned using Excel to remove any missing values and ensure consistency in data types.

<img width="971" alt="2023-04-22 (1)" src="https://user-images.githubusercontent.com/130006517/233794327-f156eeed-d803-4aad-a64f-9eb1d6701f9c.png">
<img width="971" alt="2023-04-22 (2)" src="https://user-images.githubusercontent.com/130006517/233794343-a80e3389-d328-4c4d-bd68-17e93539b2de.png">
<img width="971" alt="2023-04-22 (3)" src="https://user-images.githubusercontent.com/130006517/233794348-c29ccf62-d88a-459b-a806-02496ee1657c.png">
<img width="971" alt="2023-04-22 (4)" src="https://user-images.githubusercontent.com/130006517/233794351-1d63a51f-0fa5-4c9b-84a4-4b4bcf4d4dec.png">
<img width="971" alt="2023-04-22" src="https://user-images.githubusercontent.com/130006517/233794354-f83ff1b5-8866-442d-8e11-56527fd56823.png">


Exploratory data analysis: Basic descriptive statistics and visualizations were generated using SQL to get a better understanding of the dataset, including mean, median, standard deviation, and histograms.

Correlation analysis: Correlation matrices were generated using SQL to identify any significant correlations between variables.


Results
The analysis revealed several important findings:

Features such as radius, texture, and perimeter were strongly correlated with malignancy.

A logistic regression model was built that predicted malignancy with high accuracy.

A decision tree was generated that identified radius as the most important predictor of malignancy.

The ROC curve analysis showed that the logistic regression model had a high AUC score, indicating good predictive power.

Conclusion
The analysis of the prostate cancer dataset using SQL revealed several important insights into the factors that contribute to malignancy. The results suggest that features such as radius, texture, and perimeter are strongly correlated with malignancy, and that a logistic regression model built on these features can predict malignancy with high accuracy. The decision tree analysis identified radius as the most important predictor of malignancy, which could be useful for clinical decision-making. Overall, the project demonstrates the value of using SQL for data analysis, particularly in the context of medical research.

Future Work
There are several potential avenues for future work with this analysis. One possibility is to explore other machine learning models, such as support vector machines or random forests, to see if they can achieve even higher predictive accuracy. Another possibility is to explore other datasets related to prostate cancer or other types of cancer to see if similar insights can be gained. Finally, it may be useful to collaborate with medical professionals to gain a better understanding of how the results of this analysis can be applied in a clinical setting.



