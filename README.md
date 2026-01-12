# Cancer-data-Analysis

# Global Cancer Data Analytics (2015–2024)
# Project Overview

This repository contains a comprehensive data analysis of global cancer patient data spanning a decade (2015–2024). The project explores the relationships between various risk factors—such as genetics, smoking, air pollution, and obesity—and their impact on cancer severity, survival rates, and treatment costs.
Dataset Description

# The analysis uses a dataset of 50,000 patient records with 15 unique attributes:

    Demographics: Patient ID, Age, Gender, and Country/Region.

    Risk Factors: Genetic Risk, Air Pollution exposure, Alcohol Use, Smoking habits, and Obesity Level.

    Clinical Data: Cancer Type (e.g., Lung, Leukemia, Breast, Skin), Cancer Stage (Stage 0 to Stage IV), and Target Severity Score.

    Financial & Outcomes: Treatment Cost (USD) and Survival Years.

# Key Analytics & Insights

    Descriptive Analysis: Statistical summaries of patient demographics and risk factor distributions.

    Statistical Modeling:

        Multiple Linear Regression: Utilized to determine how genetic risk and smoking independently or jointly influence the Target Severity Score.

        Interaction Effects: The study specifically tested the hypothesis that genetic risk amplifies the effects of smoking. Results indicated that the interaction effect was not statistically significant (p = 0.628), suggesting these factors may act independently.

    Visualization: Detailed plots using Seaborn and Matplotlib to identify trends in treatment costs and survival metrics across different cancer types and stages.

# Technologies Used

    Language: Python

    Libraries: * pandas & numpy: Data manipulation and numerical analysis.

        seaborn & matplotlib: Data visualization.

        scipy/statsmodels: Statistical testing and regression modeling.

# How to Run

    Ensure you have Python installed.

    Install required dependencies:
    Bash

# pip install pandas numpy seaborn matplotlib

Open the cancer_data_analytics(1).ipynb file in Jupyter Notebook or Google Colab.

Update the data path in the second cell to point to your local copy of global_cancer_patients_2015_2024.csv.
