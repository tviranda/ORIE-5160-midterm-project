# ORIE-5160 Midterm Project: HeartSteps Analysis

## Project Overview
This project analyzes data from the HeartSteps mobile health intervention to investigate how different types of activity suggestions ("active" vs. "sedentary") affect physical activity and user engagement. The data includes minute-by-minute step counts from the Jawbone tracker and Google Fit, along with notification data.

## Problem Statement
We aim to answer the following questions:
- Which activity suggestion framing ("active" vs. "sedentary") leads to better health outcomes (e.g., steps, active minutes)?
- Which framing results in faster user engagement (e.g., time until physical activity after a notification)?

### Exploratory Analysis
We will explore how user location and self-efficacy influence the effectiveness of these suggestions.

## Repository Structure
```
heartsteps_project/
│
├── data/
│   ├── heartsteps_data.csv       # Main dataset
│   └── user_survey_data.csv      # User survey responses
│
├── dslc_documentation/           # Data Science Life Cycle documentation
│
├── functions/
│   ├── 01_cleaning.ipynb         # Data cleaning script
│   ├── 02_eda.ipynb              # Exploratory Data Analysis
│   ├── 03_dimensionality_reduction.ipynb  # Dimensionality reduction techniques
│   └── 04_clustering.ipynb       # Clustering analysis
│
└── README.md                     # Project overview and instructions

```


## Methodology (PCS Framework)
1. **Problem Formulation**: Investigate how activity suggestion framing impacts physical activity.
2. **Data Cleaning & Preprocessing**: Handle missing data, standardize timestamps, and merge step counts with notification data.
3. **EDA**: Visualize step counts and engagement times based on suggestion type.
4. **Dimensionality Reduction**: Use PCA to reduce the dimensionality of high-volume datasets.
5. **Predictive Analysis**: Run t-tests, regression models to compare framing impacts on activity and engagement.
6. **Evaluation**: Use cross-validation for result validation.

## Conjectures
1. Active suggestions will lead to more steps and faster engagement.
2. Self-efficacy and location will moderate the impact of the suggestions.

## GitHub Repository
Collaborate with us on this project: [GitHub Repository Link](https://github.com/Kataraduo/ORIE-5160-midterm-project.git)
