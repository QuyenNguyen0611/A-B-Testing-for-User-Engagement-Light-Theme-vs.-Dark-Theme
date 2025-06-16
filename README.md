# A/B Testing: Light vs. Dark Theme Performance 

This project analyzes user interaction data from an online bookstore to evaluate the performance of two website themes — Light Theme (existing design) and Dark Theme (new design). The goal is to guide business decisions by identifying whether one theme drives better user engagement and conversion through statistical analysis and data visualization.

## Business Objective
To determine which website theme leads to higher conversion rates and overall better user experience, helping the platform improve design choices to maximize purchases, session engagement, and user retention.

## Key Research Questions
- Which theme is associated with higher conversion rates?
- How do engagement metrics like bounce rate, session duration, and scroll depth vary by theme?
- Is there a statistically significant difference in user behavior between themes?
- Do theme preferences differ by demographics (e.g., age, location)?

## Dataset
Source: [Kaggle - Light Theme and Dark Theme: Case Study](https://www.kaggle.com/datasets/romanniki/light-theme-and-dark-theme-case-study/data) \
Key columns:
- **Theme**: Indicates which version of the website (Light or Dark) the user interacted with.
- **Click Through Rate (CTR)**: Proportion of users who clicked on any links or buttons during their session — a measure of engagement.
- **Conversion Rate**: Percentage of users who signed up for an account after their first visit.
- **Bounce Rate**: Percentage of users who exited the website after viewing only one page — a key indicator of disinterest or poor user experience.
- **Scroll Depth**: How far down users scrolled on the website page, used to gauge content consumption and interaction depth.
- **Age**: The user's age, useful for demographic analysis.
- **Location**: The user’s geographical location.
- **Session Duration**: The total time a user spent on the website during a session.
- **Added_to_Cart**: Indicates whether the user added any books to their shopping cart (Yes/No).
- **Purchases**: Whether the user completed a purchase during their session (Yes/No).

## Methodology
- Data Cleaning & EDA: Ensured data types and completeness, explored metric distributions and trends.
- Visual Analysis: Used plotly, seaborn, and matplotlib for insightful comparisons.
- Statistical Testing:\
Proportion Z-Test for comparing conversion rates between themes.\
Two-Sample T-Test for comparing average session durations.

## Key Findings
- Conversion Rate: Slightly higher for Dark Theme but not statistically significant (p = 0.39).
- Session Duration: Slight difference between themes, also not statistically significant (p = 0.72).
- Engagement Metrics: Light Theme showed marginally better bounce rate and scroll depth.

## Conclusion: 
No compelling evidence that one theme significantly outperforms the other. Differences appear due to random variation.

## Tools & Libraries
- Languages: Python (pandas, matplotlib, seaborn, plotly, scipy, statsmodels)
- Platform: Google Colab
  
## Files Included
Complete notebook with code, analysis, and plots is available [here](https://github.com/QuyenNguyen0611/A-B-Testing-for-User-Engagement-Light-Theme-vs.-Dark-Theme/blob/main/Theme_A_B_Testing_with_Python.ipynb)

Report is available [here](https://github.com/QuyenNguyen0611/A-B-Testing-for-User-Engagement-Light-Theme-vs.-Dark-Theme/blob/main/A%3AB%20Testing%20for%20User%20Engagement%20Light%20Theme%20vs%20Dark%20Theme.pdf)
