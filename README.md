# Factors Determining Hospital Readmissions

## Table of Contents
  - Project Overview

  - Tools

  - Data Cleaning
    
  - Exploratory Data Analysis

  - Supervised Machine Learning

  - Insights

### Project Overview
Hospital patient readmission refers to the scenario where a patient, who has recently been discharged from a hospital, returns to the same hospital for additional medical care within a specified time frame. Readmissions are often monitored as a key healthcare quality metric, and efforts are made to reduce them. High rates of readmission may indicate issues with the initial treatment, discharge process, or ongoing care. 
This Supervised Machine learning data science project aims to generate insights and creates a model that effectively predicts and better understand the probability of readmission.

### Tools
 - Python - Data Analysis
 - Matplotlib - For Data Visualizations
 - Seaborn - For Data Visualizations
 - Numpy
 - Pandas
 - Scikit-learn
 - Jupyter notebook - Coding Environment 

### Data Cleaning
In the data preparation phase, i performed the following tasks;

1. Data loading
2. Data Validation
3. Data cleaning
4. Handling Missing Values

### Exploratory Data Analysis
EDA involved exploring the Patient Sleep Disorder Data to answer key questions such as;

 - What is the most common primary diagnosis by age group.
 - What is the effect of a diabetes diagnosis on readmission rates.
 - What groups of patients should the hospital focus their follow-up efforts to better monitor patients with a high probability of readmission?
 
### Supervised Machine Learning
Supervised machine learning is a type of machine learning where the algorithm is trained on a labeled dataset, meaning that the input data is paired with corresponding output labels. The goal of supervised learning is to learn a mapping or relationship between input features and their corresponding output labels, allowing the algorithm to make predictions or classifications on new, unseen data. .  RandomForest Classifier and DecisionTree Classifier was used due to their effectiveness in classification tasks.

### Insights
1.Circulatory diagnosis was the most common primary diagnosis across the varoius categories of age outside early middle age where Others as a diagnosis category came first and circulatory diagnosis second.

2.On the effects of diabetes diagnosis on readmission ,the analysis doesnt confirms if diabetes plays a central role in readmission as they could be other factors causing patients readmission but we can deduct that majority of the patients had diabetes as a diagnosis logically making them occupy a high readmission rates

### Recommendations
I would recommend for the hospital to focus their follow-up efforts to better monitor patients :

 - who have had high number of inpatient visits in the year before the hospital stay ,that is patient whe had currently been admitted in the hospital before
 - who have had high number of outpatient visits in the year before the hospital stay, that is patient who had frequented the hospital as an outpatient
 - patients who are on plenty medications
 - patients who under go various lab procedures
 - patients who had being brought to the hospital as an emergency situation before current hospital stay
they are very important factors to be considered as they have a high probability to determine if a patient wil be readmitted.

​
