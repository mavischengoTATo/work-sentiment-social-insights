# Work Attitudes and Job Hunting Insights

## About Me

A brief introduction about the author and their interest in exploring attitudes toward work and the job-hunting process through data science.

## Code

This section contains code for all aspects of the analysis, including data gathering, data cleaning (in both Python and R), exploratory data analysis, and various machine learning models.

## Data

This project uses data from two primary sources:
1. **Social Media Data from Twitter**: Tweets about work, job hunting, and related topics to understand public sentiment.
2. **Job Dataset**: Data with job titles, departments, pay rates, and descriptions to analyze job characteristics and compensation trends.

## Introduction

In this project, we explore two main points:
1. How data science can help people with job hunting.
2. People’s attitudes toward work, especially post-COVID-19, where perspectives vary from pessimistic to optimistic.

We collect Twitter data to analyze public opinion on work and use a job dataset to examine compensation and job descriptions. Through this, we aim to answer various questions about work trends, attitudes, and job hunting.

## Data Gathering

Data is gathered from Twitter using keywords related to work, job hunting, and job titles. Additionally, job data is collected from existing datasets to analyze salary trends, job descriptions, and department impact.

## Data Cleaning

- **Data Cleaning (Python)**: Cleaning and preprocessing the data in Python for consistency and analysis readiness.
- **Data Cleaning (R)**: Alternative data cleaning and preprocessing steps in R to handle specific data types or perform initial exploration.

## Exploring Data

Exploratory Data Analysis (EDA) to understand the structure and relationships within the dataset. This includes visualizing trends in work attitudes, compensation, and public sentiment from Twitter data.

## Naive Bayes (Python)

Naive Bayes model implemented in Python for text classification of job descriptions, aimed at predicting salary level and position rank.

## Naive Bayes (R)

Alternative Naive Bayes implementation in R for the same classification task, providing additional insights or comparisons.

## Decision Trees

Using Decision Tree models to predict salary levels based on job description and other job-related variables.

## SVM

Support Vector Machine (SVM) models to enhance classification and prediction accuracy, particularly focusing on job description analysis.

## Clustering

Clustering techniques to segment job market data and identify patterns within job titles, departments, and compensation structures.

## ARM and Networking

Association Rule Mining (ARM) and network analysis to uncover hidden relationships between job characteristics and public attitudes towards work.

## Conclusions

Throughout this project, we explored the term "work" to understand various perspectives through Twitter data and job datasets. Initially, we set out to answer ten specific questions, though not all could be fully addressed. Here’s a summary of key findings:

1. **Job Market Data Limitations**: The job dataset lacked sufficient variables and consistency in job titles, making it difficult to explore the relationship between working years, department, and compensation. Future work could benefit from a more detailed dataset.

2. **Text Analysis Challenges**: Attempts to classify job descriptions by salary level and position rank with Naive Bayes faced issues due to data imbalance and inconsistencies in job descriptions. Real-life variations in job postings limited the effectiveness of the model.

3. **Job Title Variations**: Job titles vary significantly across companies, which affects standardization. We recommend using formal recruitment platforms where job titles and descriptions follow standardized options, enhancing data reliability.

4. **Twitter Analysis**: Our Twitter analysis demonstrated that specific keywords and phrases correlate with higher engagement rates (retweets and likes), indicating that phrasing influences the visibility of work-related posts. This has implications for individuals or brands seeking to maximize social media engagement.

This project provided valuable insights into attitudes toward work and job hunting. While limitations in data and modeling were encountered, future improvements could focus on refining datasets and exploring more sophisticated NLP models. This project is a stepping stone, illustrating data science's potential to influence job market insights and social media engagement strategies.

