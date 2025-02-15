# Lung Cancer Early Detection: 
## Helping people forcast the likelihood of developing lung cancer

### Table of Contents

1. [Contributors](#contributors)
2. [Executive Summary](#executive-summary)
3. [Key Points to Consider](#key-points-to-consider)
4. [Project Objectives](#project-objectives)
5. [Research Approach](#research-approach)
6. [Datasets](#datasets)
7. [Analysis and Conclusion](#analysis-and-conclusion)
8. [Next Steps](#next-steps)
9. [Tools and Libraries](#tools-and-libraries)
10. [How To Run](#how-to-run)
11. [License](#license)

### Contributors

![contributors](team-picture.png)

Contributors to the project, pictured from left to right:
1. **Cameron Keplinger**
2. **Eshumael Manhanzva**
3. **Sowmya Shetty**
4. **Luther Johnson**
5. **Saurabh Pratap Singh**
4. **Valarie Miller**
5. **Sunil Khambaita (Advisor)**

### Executive Summary 

To help people identify their likelihood of developing lung cancer based on a variety of factors including age, environment and health. 

### Key Points to Consider

1. **Age**
2. **Environment**
3. **Access to Good Healthcare**
4. **Smoking Habbits**

### Project Objectives

#### 1. **Data Collection & Cleaning**

This dataset offers important insights into lung cancer cases, risk factors, smoking trends, and healthcare access in 25 of the world’s most populated countries. It includes information on 220,632 individuals, detailing their age, gender, smoking history, cancer diagnosis, environmental exposure, and survival rates. This dataset is instrumental for medical research, predictive modeling, and policy-making to understand global lung cancer patterns.

#### Data source: https://www.kaggle.com/datasets/ankushpanday1/lung-cancer-risk-and-trends-across-25-countries
25 of the world’s most populated countries

Environment

Smoking habits

Access to Healthcare

#### 2. **Approach & Methodology**

Our approach will be to utilize the following: 
Clustering: Cluster countries based on lung cancer risk factors using:
Population, annual lung cancer deaths, lung cancer prevalence, mortality rate, air pollution, exposure, occupational exposure, indoor pollution, access to good healthcare
Clustering: Cluster according to risk level, of low, medium, high. For example, 
	Low: young, non-smoker, good healthcare access
	Medium: (family history, poor environment) 
	High: older, smoker, poor health care 

 #### 3. **Models in Use**

Supervised Learning 
Classification -  identify car makes and models popularity across cities
Target variable - vehicle.type
Feature columns 
Tools - Classification tools 
RandomForest

Linear Regression - Predict # of times a car make/model will be rented in a given city
Target Variable - number of renters
Unsupervised Learning 
Group vehicles into  clusters based on how frequently they are being rented 
KMeans - (Clustering)

Models to use	
Random Forest (Decision Tree based model used for  Regression / classification) 
Decision Tree - (Random Forest/Classification)

Both Supervised & Unsupervised Learning Methodology

### 4. **Tools & Techniques**

Pandas & Pandas Plotting
Python
Scikit-learn
Matplotlib
Numpy



