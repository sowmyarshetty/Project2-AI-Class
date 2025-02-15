# Lung Cancer Early Detection: 
## Helping people forcast the likelihood of developing lung cancer

### Table of Contents

1. [Contributors](#contributors)
2. [Executive Summary](#executive-summary)
3. [Key Points to Consider](#key-points-to-consider)
4. [Project Objectives](#project-objectives)
5. [Approach & Methodology](#approach-&-methodology)
6. [Data Collecting & Cleaning](#data-collecting-&-cleaning)
7. [Models](#models)
8. [Next Steps](#next-steps)
9. [Tools and Libraries](#tools-and-libraries)
10. [How To Run](#how-to-run)
11. [License](#license)

### Contributors

![contributors](team-picture.png)

Contributors to the project, pictured from left to right:
* **Cameron Keplinger**
* **Eshumael Manhanzva**
* **Sowmya Shetty**
* **Luther Johnson**
* **Saurabh Pratap Singh**
* **Valarie Miller**
* **Sunil Khambaita (Advisor)**

### Executive Summary 

To help people identify their likelihood of developing lung cancer based on a variety of factors including age, environment and health. This project analyzes a lung cancer dataset using classification, regression, and clustering.

We aim to:

* Predict lung cancer diagnosis using **classification**
* Predict lung cancer diagnosis using **logistic regression, Decision Tree , RandomForestClassifer**
* Identify clusters of patients based on risk factors using **K-Means clustering**

### Key Points to Consider

* **Age**
* **Environment**
* **Access to Good Healthcare**
* **Smoking Habbits**

### Project Objectives

#### 1. **Data Collection & Cleaning**

This dataset offers important insights into lung cancer cases, risk factors, smoking trends, and healthcare access in 25 of the world’s most populated countries. It includes information on 220,632 individuals, detailing their age, gender, smoking history, cancer diagnosis, environmental exposure, and survival rates. This dataset is instrumental for medical research, predictive modeling, and policy-making to understand global lung cancer patterns.

#### Data source: https://www.kaggle.com/datasets/ankushpanday1/lung-cancer-risk-and-trends-across-25-countries
25 of the world’s most populated countries

* Environment
* Smoking habits
* Access to Healthcare

#### 2. **Approach & Methodology**

Our approach utilizes the following: 
Clustering: Cluster countries based on lung cancer risk factors using:
* Population, annual lung cancer deaths, lung cancer prevalence, mortality rate, air pollution, exposure, occupational exposure, indoor pollution, access to good healthcare
* Clustering: Cluster according to risk level, of low, medium, high. For example, 
	* Low: young, non-smoker, good healthcare access
	* Medium: (family history, poor environment) 
	* High: older, smoker, poor health care 

#### Exploratory Data Analysis
#### Classification: Predicting Lung Cancer Diagnosis

#### 3. **Models**

#### Classification - Random Forest Classifier Model 

#### Decision Tree Model

#### Clustering: K-Means with Elbow Method

Both Supervised & Unsupervised Learning Methodology

#### 4. **Tools & Techniques**

* Pandas & Pandas Plotting
* Python
* Scikit-learn
* Matplotlib
* Numpy



