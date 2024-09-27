# loan-defaulter-EDA

## Project Description
This project involves performing exploratory data analysis (EDA) on a CSV dataset provided by the university. The analysis aims to identify patterns and insights related to loan defaulters, helping to understand the characteristics of individuals who may be at risk of defaulting on loans.

## Table of Contents
- [Project Structure](#project-structure)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Data Description](#data-description)
- [Analysis Overview](#analysis-overview)
- [Key Insights](#key-insights)
- [Conclusion and Recommendations](#conclusion-and-recommendations)

## Project Structure
- `final eda assignment.ipynb` - The main Python script where the exploratory data analysis (EDA), outlier treatment, and visualizations are performed.
- `eda assignment preprocessing.ipynb` - Script containing data preprocessing steps, including handling missing values and scaling.
- `Assignment on EDA.pdf` - Contains a PowerPoint presentation in PDF format, summarizing the problem statement, approach, analysis, and insights.
- `README.md` - This file, provides an overview of the project, analysis, and instructions for setup and usage.

**Note**: Original files related to this project are not shared publicly as they are part of my academic assignments.

## Installation Instructions
To run the analysis, ensure you have the following prerequisites installed:
- Python (3.8)
- Jupyter Notebook or Google Colab.
- Necessary libraries: pandas, numpy, matplotlib.pyplot, seaborn

## Usage

1. Run `final eda assignment.ipynb` for the data cleaning, data preprocessing, exploratory data analysis, visualizations, and insights.
2. Review the `Assignment on EDA.pdf` for a detailed explanation of the findings.


## Data Description
- application_data: Contains information about the current application of the client, including details such as age, occupation, and income.
- previous_application: Contains records of previous applications, detailing the status (approved, declined, canceled, or unused).
- columns_description: Provides definitions for the columns in the above datasets.

## Analysis Overview

- **Univariate Analysis:** A detailed examination of individual variables to understand their distributions, including the use of visualizations like histograms and box plots.
- **Bivariate Analysis:** Exploration of relationships between key variables, identifying patterns and correlations through scatter plots and correlation matrices.
- **Outlier Detection and Treatment:** Identified and treated outliers using statistical methods (such as IQR or Z-scores) to ensure the accuracy of the analysis and avoid skewed results. Visualized outliers through box plots and applied appropriate treatments (e.g., capping, transformation, or removal).

**Key Insights:**
- Gender-Based Defaulting: The analysis indicates that males are more likely to default on loans compared to females, based on the observed male-to-female ratio.
- Income Range: The majority of defaulters belong to the income range of 1 lakh to 2 lakhs, highlighting a potential risk group for loan providers.
- Occupation-Based Defaulting: Laborers and individuals with unknown occupations show a high rate of loan defaults, making them a significant group for further investigation.
- Sector-Based Analysis: Clients from working and commercial sectors have the highest default rates, while students and businessmen exhibit a lower likelihood of defaulting, making them more trustworthy borrowers.


## Conclusion and Recommendations

- Income-Based Reliability: Clients with an income greater than 5 lakhs are generally reliable and should be prioritized for loans. In contrast, those earning less than 2 lakhs have a high default rate and are less trustworthy.
- Occupation-Based Reliability: Clients working as realty agents, IT staff, and HR staff tend to be reliable, while laborers have a higher default risk and should be approached cautiously.
- Family Accompaniment: Clients accompanied by children are more reliable, whereas unaccompanied clients are not as trustworthy.
- Sector-Based Reliability: Students and businessmen are typically reliable borrowers, but clients from the working and commercial sectors exhibit higher default rates and may not be the best candidates for loans.
- Loan Purpose Transparency: Clients who do not provide a clear reason for their loan request are mostly defaulters and should be avoided by banks to minimize risk.
