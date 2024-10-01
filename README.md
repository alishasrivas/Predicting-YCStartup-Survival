# Predicting Y Combinator Startups Performance: Logistic Regression

## 🚀 Project Overview

This project aims to predict the performance of Y Combinator startups using logistic regression. Our goal is to understand the key factors that contribute to the success of startups in the Y Combinator ecosystem and to explore what criteria Y Combinator looks for when evaluating potential startups for acceptance.

## 💡 Inspiration

The inspiration for this project came when a friend of ours was rejected from Y Combinator. We decided to leverage our skills in data analysis and machine learning to investigate the underlying patterns and criteria that could help aspiring founders improve their chances of success.

## Dataset

We are utilizing a Kaggle dataset containing information about all Y Combinator startups. This dataset includes various attributes related to each startup, which we will analyze to identify trends and factors influencing their performance.

## ⏰ Current Stage

We are currently in the Exploratory Data Analysis (EDA) phase, where we examine the dataset, clean the data, and visualize relationships between variables. After completing the EDA, we will implement logistic regression to model the performance of the startups.

## Variables of Interest

The variables we are considering for regression have been designed based on financial and entrepreneurial theories. Some of the key factors we are examining include:

- **Description Word Count:** Analyzing the length of startup descriptions as a potential indicator of success.
- **Location:** Investigating the impact of geographic location on opportunities for startups.
- **Ivy League Connections:** Exploring whether the founders' educational backgrounds, particularly from Ivy League institutions, play a role in success.
- **Team Size:** Examining the size of the company to see if it correlates with better performance.
- **Is FAANG:** Checking if the founder worked at a FAANG company (Facebook, Amazon, Apple, Netflix, Google) prior to founding the startup, and how that experience impacts success.
- **Field of Study:** Considering the founder’s college field of study to explore if it is related to success, particularly in tech-related startups.

## Future Work

After completing the EDA and regression modeling, we plan to:

- Interpret the results of the logistic regression to identify significant predictors of success.
- Provide actionable insights for future Y Combinator applicants based on our findings.
- Explore additional machine learning techniques to improve our predictive model.

## Getting Started

To run this project, clone the repository and ensure you have the necessary libraries installed. You can install the required packages using the following command:

```bash
pip install -r requirements.txt
