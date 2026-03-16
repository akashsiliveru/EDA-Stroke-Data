#  Exploratory Data Analysis on Stroke Dataset

##  Project Overview

Stroke is one of the leading causes of death and long-term disability worldwide. Early identification of risk factors can help in prevention and treatment.
This project performs **Exploratory Data Analysis (EDA)** on a stroke dataset to identify important patterns, relationships, and risk factors that may influence the occurrence of stroke.
The analysis focuses on understanding how variables such as **age, hypertension, heart disease, glucose levels, BMI, smoking status, and lifestyle factors** relate to stroke occurrence.

##  Problem Statement

The objective of this project is to explore the dataset and identify **key factors associated with stroke risk** through statistical analysis and data visualization.

The analysis helps answer questions such as:

- Which factors are strongly associated with stroke?
- How does age influence stroke probability?
- Do lifestyle factors like smoking or BMI impact stroke risk?
- Are there differences in stroke occurrence across demographic groups?


## Dataset

The dataset contains health and demographic information for individuals, including medical history and lifestyle factors.

### Dataset Features

| Feature | Description |
|------|-------------|
| id | Unique identifier |
| gender | Gender of the patient |
| age | Age of the patient |
| hypertension | Whether the patient has hypertension |
| heart_disease | Whether the patient has heart disease |
| ever_married | Marital status |
| work_type | Type of employment |
| Residence_type | Urban or Rural residence |
| avg_glucose_level | Average glucose level in blood |
| bmi | Body Mass Index |
| smoking_status | Smoking status |
| stroke | Target variable indicating stroke occurrence |

##  Steps Performed

###  Data Loading
- Imported dataset using **Pandas**
- Loaded data into a Jupyter Notebook environment

###  Data Exploration
- Examined dataset structure
- Checked data types
- Generated summary statistics
- Identified missing values

###  Data Cleaning
- Handled missing values
- Verified data consistency
- Removed unnecessary columns if required

###  Univariate Analysis
Analyzed distributions of individual variables using:

- Histograms
- Count plots
- Box plots

###  Bivariate Analysis
Explored relationships between features and stroke occurrence using:

- Scatter plots
- Box plots
- Bar charts
- Correlation analysis

###  Outlier Detection
Used boxplots to detect potential outliers in numerical variables such as **age, glucose level, and BMI**.


##  Visualizations

Several visualizations were used to understand the dataset:

- **Histogram** – Distribution of age, BMI, and glucose levels
- **Count Plot** – Distribution of categorical variables
- **Box Plot** – Outlier detection and comparison across groups
- **Bar Plot** – Stroke occurrence across categories
- **Correlation Heatmap** – Relationships between numerical variables
- **Scatter Plot** – Relationship between BMI, glucose levels, and stroke

These visualizations help identify **patterns and potential risk factors**.

## Key Insights

- Stroke cases are more common among **older individuals**.
- Individuals with **hypertension and heart disease** show higher stroke risk.
- **Higher glucose levels** appear associated with stroke occurrence.
- Lifestyle factors such as **smoking and BMI** may influence stroke risk.
- Certain demographic and employment categories show differences in stroke distribution.

## Tools & Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
## Statistics Concepts Applied

![Descriptive Statistics](https://img.shields.io/badge/Descriptive%20Statistics-4CAF50?style=flat)
![Probability Distributions](https://img.shields.io/badge/Probability%20Distributions-2196F3?style=flat)
![Hypothesis Testing](https://img.shields.io/badge/Hypothesis%20Testing-FF9800?style=flat)
![Central Limit Theorem](https://img.shields.io/badge/Central%20Limit%20Theorem-3F51B5?style=flat)



---

⭐ If you found this project helpful, feel free to **star the repository**!
