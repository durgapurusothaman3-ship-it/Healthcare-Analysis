                            Healthcare Patient Analysis System (Synthetic Data)
Project Overview

The Healthcare Patient Analysis System is a data analytics project that generates and analyzes synthetic patient health records. Since real healthcare datasets are often restricted due to privacy concerns, this project uses artificially generated patient data to simulate real-world healthcare scenarios.

The system performs Exploratory Data Analysis (EDA) on patient health metrics such as blood pressure, sugar level, cholesterol, and heart rate. It classifies patients into different risk categories, identifies high-risk individuals, and provides visual insights that can support healthcare monitoring and decision-making.

Problem Statement

Healthcare institutions generate large volumes of patient data every day. Manually analyzing these records is time-consuming, inefficient, and prone to human errors.

Due to privacy regulations, obtaining real patient data for academic projects is challenging. Therefore, this project develops an automated system that generates synthetic patient data and performs detailed analysis to identify patterns, trends, and health risks.

Objectives

The primary objective of this project is to perform Exploratory Data Analysis (EDA) on a synthetic healthcare dataset.

Specific Objectives
Generate a synthetic dataset containing 10,000 patient records.
Perform data cleaning and preprocessing.
Analyze important health parameters:
Blood Pressure
Sugar Level
Cholesterol
Heart Rate
Calculate descriptive statistics:
Mean
Median
Mode
Standard Deviation
Classify patients into:
Low Risk
Medium Risk
High Risk
Identify high-risk patients requiring attention.
Compare health conditions across:
Different age groups
Gender categories
Study relationships between health variables.
Visualize healthcare data using charts and graphs.
Generate meaningful healthcare insights.
Dataset Description

The dataset consists of 10,000 synthetic patient records.

Column Name	Description	Range
Patient_ID	Unique Patient Identifier	1–10000
Age	Patient Age	20–80
Gender	Male/Female	Categorical
Blood_Pressure	Blood Pressure Reading	80–180
Sugar_Level	Blood Sugar Level	70–200
Cholesterol	Cholesterol Level	150–300
Heart_Rate	Heart Rate	60–120
Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Jupyter Notebook
Project Structure
Healthcare-Patient-Analysis-System/
│
├── healthcare_analysis.ipynb
├── healthcare_data.csv
├── README.md
├── images/
│   ├── risk_distribution.png
│   ├── age_distribution.png
│   ├── heatmap.png
│   └── scatter_plot.png
│
└── requirements.txt
