# Insurance Cost Analysis (EDA with Python)



A data analysis project exploring the key factors that influence medical insurance charges using visual insights.

---

## Project Overview

In this project, I performed an exploratory data analysis on a medical insurance dataset to understand what drives insurance costs. The dataset includes features such as age, BMI, number of children, smoking status, region, and charges.

The goal was simple: uncover patterns, relationships, and trends that explain why some individuals pay significantly more for insurance than others.

---

## Data Exploration Journey

I began by examining the structure and quality of the dataset. After confirming there were no missing values and removing a duplicate entry, I explored the distributions and relationships between variables.

Categorical features like gender, smoking status, and region were analyzed visually to understand their composition. These were later encoded into numeric values to allow deeper analysis, especially correlation.

---

## Key Insights from the Analysis

### 1. Smoking is the Biggest Cost Driver

The most striking insight from the analysis is the impact of smoking on insurance charges. Smokers consistently show significantly higher charges compared to non-smokers. This strong positive relationship stands out clearly in both correlation analysis and scatter plots.

Conclusion: Smoking is the most influential factor in determining insurance costs.

---

### 2. Age Has a Strong Positive Relationship with Charges

As age increases, insurance charges also tend to increase. Older individuals generally incur higher medical costs, which is reflected in the pricing.

Conclusion: Age is a key factor, with costs rising steadily over time.

---

### 3. BMI Shows a Moderate Impact

Body Mass Index (BMI) has a noticeable but weaker relationship with charges. Individuals with higher BMI values tend to have higher costs, but the pattern is not as strong or consistent as smoking or age.

Conclusion: BMI contributes to cost variation, but is not the dominant factor.

---

### 4. Number of Children Has Minimal Influence

The number of children does not show a strong relationship with insurance charges. The variation in costs remains fairly spread out regardless of family size.

Conclusion: Family size is not a major cost driver in this dataset.

---

### 5. Gender Does Not Significantly Affect Charges

The distribution of charges between males and females appears relatively balanced, with no clear pattern suggesting one group consistently pays more.

Conclusion: Gender has little to no impact on insurance pricing.

---

### 6. Region Has Very Little Effect

Insurance charges are fairly evenly distributed across different regions. No region stands out as significantly more expensive than others.

Conclusion: Location (within this dataset) does not strongly influence cost.

---

### 7. Data Distribution Observations

* BMI values follow a roughly normal distribution
* Charges are right-skewed, meaning a smaller group of individuals pay significantly higher costs
* Most individuals are non-smokers, which explains why lower charges are more common overall

---

## Correlation Insights

Correlation analysis confirmed the visual findings:

* Smoking and age have the strongest positive relationships with charges
* BMI has a moderate correlation
* Other variables show weak or negligible relationships

---

## Final Takeaway

This analysis highlights that lifestyle choices (especially smoking) and age are the primary drivers of medical insurance costs. While other factors like BMI contribute to some extent, they are far less influential.

---
