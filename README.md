# Predicting Y Combinator Startup Survival: Machine Learning

## 🚀 Project Overview

This project aims to predict the performance of Y Combinator startups using survival analysis techniques in machine learning and statistics. Our goal is to understand the key factors that contribute to the success of startups in the Y Combinator ecosystem and to explore what criteria Y Combinator looks for when evaluating potential startups for acceptance.

## 💡 Inspiration

The inspiration for this project came when a friend of ours was rejected from Y Combinator. We decided to leverage our skills in statistics and machine learning to investigate the underlying patterns and criteria that could help aspiring founders like us improve their chances of success.

## 👩🏻‍💻 Contributors
<table>
  <tr>
    <td align="center"><a href="https://github.com/alishasrivas"><img src="https://avatars.githubusercontent.com/alishasrivas" width="100px;" alt=""/><br /><sub><b>Alisha Srivastava</b></sub></a></td>
    <td align="center"><a href="https://github.com/collaborator1"><img src="https://avatars.githubusercontent.com/siddarvind" width="100px;" alt=""/><br /><sub><b>Siddanth Arvind</b></sub></a></td>
  </tr>
</table>

## Dataset

We are utilizing a Kaggle dataset on Y Combinator startups, augmented with additional features we built using external data from scraping & APIs. This includes funding data, founder characteristics, and program-specific metrics such as the YC batch size and time to acquisition. https://www.kaggle.com/datasets/sashakorovkina/ycombinator-all-funded-companies-dataset/data?select=founders.csv 

## ⏰ Current Stage

We are currently integrating exploratory data analysis (EDA) with survival-specific methods, such as Kaplan-Meier survival curves. Feature engineering is ongoing, focusing on creating meaningful predictors for the survival models.

## 🎯 Survival Definitions

Primary Survival
-**Definition:** A startup is considered to have survived if it is acquired or remains operational (not defunct) after completing the YC program.
- **Event Indicator:** Binary (1 if acquired, 0 otherwise).
Secondary Survival
- **Definition:** A startup is considered to have survived post-YC if it raises Series A funding or higher after completing the YC program.
-**Event Indicator:** Binary (1 if Series A funding is raised, 0 otherwise).
YC-Specific Feature:
Series A funding and operational status is considered only after the YC end date (start date + 3 months).

## 📊 Analytical Approach

This project combines statistical modeling and machine learning to analyze survival outcomes:
**Statistical Modeling:**
Cox Proportional Hazards Model: For identifying statistically significant predictors of survival.
**Machine Learning:**
Random Survival Forest: For capturing non-linear relationships and complex interactions between variables.

## Next Steps

After completing the EDA and regression modeling, we plan to:
**Model Development:**
- Fit and evaluate Cox Proportional Hazards and Random Survival Forest models.
- Compare performance metrics such as C-index and log-rank test results.

**Actionable Insights:**
- Identify the most influential factors affecting startup survival.
- Provide recommendations for aspiring YC founders based on the findings.

**Portfolio Showcase:**
- Incorporate visualizations and dashboards into the GitHub repository to enhance usability and presentation.

## Getting Started

To run this project, clone the repository and ensure you have the necessary libraries installed. You can install the required packages using the following command:

```bash
pip install -r requirements.txt
