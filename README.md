# Analyzing-User-Engagement-with-News-Articles-Using-A-B-Testing

## Repository Structure
- README
- CSV file containing news articles
- Jupyter notebook
- Report

## Overview
In this project, news articles are extracted from NewsAPI across three categories.The objective is to evaluate how user interaction with these articles is influenced by their time of publication.

To achieve this, articles are divided into two groups based on their publication times: 
- Group A: Articles published between 6:00 AM and 12:00 PM 
- Group B: Articles published between 6:00 PM and 12:00 AM 
Simulated engagement metrics such as views and likes are generated for each article. 
Using these metrics, along with article features such as title length, publish time, and 
category, statistical and visualization techniques were used to identify patterns and 
insights regarding user behaviour and content performance across time window.

## Hypotheses 
- Null Hypotheses (H₀): There is no significant difference in engagement between 
Group A and Group B. 
- Alternative Hypotheses (H₁): There is a significant difference in engagement 
between Group A and Group B.

## Methodology
- Data Extraction 
- Data Preparation 
- Analysis And Observation 

## Tools Used
- Python - Programming language
- Pandas - Data manipulation
- Matplotlib and Seaborn - Data visualization
- Scipy.stats - Statistical testing
- NewsAPI - Fetching live news articles

## Key Findings
- Articles published in the evening (group B) had slightly higher views and likes on average.
- A clear upward trend showing that articles with more views get more likes, suggesting visibility drives user engagement
- However, the difference in likes and views between morning and evening posts was not statistically significant at the 95% confidence level.

## Conclusion 
Time of publication alone does not strongly influence engagement other factors such as content quality, headline, source may play a bigger role.
