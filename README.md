# Python For Product

Various projects using Python for Product Analysis and Product Management, ranging from Exploratory Data Analysis to Basic Machine Learning, with a product focus

## StreamFlix - EDA
Description: Exploratory Data Analysis using Polars and Plotly to uncover customer usage and the churn rate of different customer types

## MusicNow Analytics (Python)
Description: The goal of this project is to process raw event logs and transform them into actionable product insights using modern Python data manipulation and visualization libraries.
Key Implementations:
- Synthetic Data Generation: Engineered a custom dataset of user events (including song plays, logins, ad clicks, and premium upgrades) to simulate real-world user behavior.
- Data Cleaning Pipeline: Utilized Polars to cast date strings into proper datetime objects, handle missing values, and filter relevant event streams for accurate aggregation.
- Core Product Metrics: Calculated and visualized Daily Active Users (DAU), Total Daily Streams, and Average Listen Time per Day using Plotly line and bar charts.
- Advanced Analytics: Executed a Day-1 cohort retention analysis and calculated overall free-to-premium conversion rates to evaluate user engagement and monetization.

## Feature Engagement Scorer (Python)
Description: A streamlit web app that calculates user engagement and gives recommended actions
Key Implementations:
- User input: The Product Manager is able to input the number of logins and new features per week
- Scorer: The app calculates the engagement rate for a user
- Action: The app suggests a call to action based on the user type ('Active', 'At-Risk',' Power User')

## Product Analyst Metric Converter (Python)
Description: A Streamlit web app that converts standard product management metrics and estimates agile development time.
Key Implementations:
- User input: The Product Analyst selects a conversion category (Revenue, Agile Estimation, or User Engagement) and inputs the base numbers.
- Converter: The app calculates the mathematical translations for MRR/ARR, Story Points to days (factoring in developer seniority), and DAU/MAU proxies.
- Output: The app displays the final estimated metric in a clear, formatted result block for quick reference in product meetings.
