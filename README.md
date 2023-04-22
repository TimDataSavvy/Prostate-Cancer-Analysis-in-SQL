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


Exploratory data analysis: Basic descriptive statistics and visualizations were generated using SQL to get a better understanding of the dataset, including mean, median, standard deviation, and histograms.

<img width="971" alt="2023-04-22 (2)" src="https://user-images.githubusercontent.com/130006517/233794444-4956d491-d218-4dc9-8d41-f1c0e9f5bed9.png">
<img width="971" alt="2023-04-22 (3)" src="https://user-images.githubusercontent.com/130006517/233794447-ff2f8ff4-d1fb-4ee6-a269-81aac61b9394.png">
<img width="971" alt="2023-04-22 (4)" src="https://user-images.githubusercontent.com/130006517/233794451-147c72c2-d6fb-41a7-b7a6-a8656cdca533.png">
<img width="971" alt="2023-04-22" src="https://user-images.githubusercontent.com/130006517/233794455-0474c159-f244-48c2-963b-939e2e60977c.png">



Results
The analysis revealed several important findings:

Features such as radius, texture, and perimeter were strongly correlated with malignancy.


Conclusion


The analysis of the prostate cancer dataset using SQL revealed several important insights into the factors that contribute to malignancy. The results suggest that features such as radius, texture, and perimeter are strongly correlated with malignancy, and that a logistic regression model built on these features can predict malignancy with high accuracy. The decision tree analysis identified radius as the most important predictor of malignancy, which could be useful for clinical decision-making. Overall, the project demonstrates the value of using SQL for data analysis, particularly in the context of medical research.

Future Work


There are several potential avenues for future work with this analysis. One possibility is to explore other machine learning models, such as support vector machines or random forests, to see if they can achieve even higher predictive accuracy. Another possibility is to explore other datasets related to prostate cancer or other types of cancer to see if similar insights can be gained. Finally, it may be useful to collaborate with medical professionals to gain a better understanding of how the results of this analysis can be applied in a clinical setting.



