# Lung Cancer Early Detection: 
## Helping people forcast the likelihood of developing lung cancer

### Table of Contents

1. [Contributors](#contributors)
2. [Executive Summary](#executive-summary)
3. [Key Points to Consider](#key-points-to-consider)
4. [Project Objectives](#project-objectives)
5. [Approach and Methodology](#approach-and-methodology)
6. [Models](#models)
7. [Tools and Techniques](#tools-and-techniques)
8. [How To Run](#how-to-run)
9. [License](#license)
10. [Next Steps](#next-steps)

### Contributors

![contributors](team-picture.png)

Contributors to the project:
* **Cameron Keplinger**
* **Eshumael Manhanzva**
* **Sowmya Shetty**
* **Luther Johnson**
* **Saurabh Pratap Singh**
* **Valarie Miller**
* **Sunil Khambaita (Advisor)**

### Executive Summary 

To help people identify their likelihood of developing lung cancer based on a variety of factors including age, environment and health. This project analyzes a lung cancer dataset using classification, regression, and clustering.

In this project we succefully completed the following:

* Predict lung cancer diagnosis using **classification**
* Predict lung cancer diagnosis using **logistic regression, Decision Tree , RandomForestClassifer**
* Identify clusters of patients based on risk factors using **K-Means clustering**

### Key Points to Consider

* **Age**
* **Environment**
* **Access to Good Healthcare**
* **Smoking Habbits**

### Project Objectives

#### Data Collection & Cleaning

This dataset offers important insights into lung cancer cases, risk factors, smoking trends, and healthcare access in 25 of the world’s most populated countries. It includes information on 220,632 individuals, detailing their age, gender, smoking history, cancer diagnosis, environmental exposure, and survival rates. This dataset is instrumental for medical research, predictive modeling, and policy-making to understand global lung cancer patterns.

#### Data source: https://www.kaggle.com/datasets/ankushpanday1/lung-cancer-risk-and-trends-across-25-countries

* 25 Of The World’s Most Populated Countries
* 24 Data Columns
* 220632 Total Records
* Equal Distribution of Men and Women
* Ages Range From 22 to 85 Years Old

### Approach and Methodology

Our approach utilizes the following: 
Clustering: Cluster countries based on lung cancer risk factors using:
* Population, annual lung cancer deaths, lung cancer prevalence, mortality rate, air pollution, exposure, occupational exposure, indoor pollution, access to good healthcare
* Clustering: Cluster according to risk level, of low, medium, high. For example, 
	* Low: young, non-smoker, good healthcare access
	* Medium: (family history, poor environment) 
	* High: older, smoker, poor health care 

#### Exploratory Data Analysis
#### Classification: Predicting Lung Cancer Diagnosis

###  Models

#### Logistic Regression Model - for Classification
* Acheived 100% accuraccy with the model

#### Random Forest Classifier Model 
* Acheived 100% accuraccy with the model
* Identified Top 10 Most Important Features

#### Decision Tree Model
* Acheived 100% accuraccy with the model but tree was initially too short
* Removed the some data sests from dataset to improve the decision tree 
* Acheived 97.4% accuraccy with the model after revisions

#### K-Means with Elbow Method - for Clustering

Both Supervised & Unsupervised Learning Methodology

### Tools and Techniques

* Pandas & Pandas Plotting
* Python
* Scikit-learn
* Matplotlib
* Numpy

### Next Steps

