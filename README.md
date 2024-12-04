# Customer Spending Analysis: Impact of Engagement Metrics

## Overview
This project analyzes a Kaggle dataset to explore the relationship between customer engagement metrics and their yearly spending. The goal is to understand how various engagement factors—such as **Average Session Length**, **Time on App**, **Time on Website**, and **Length of Membership**—affect the total amount spent by customers.

By identifying key patterns, businesses can optimize their strategies to increase customer spending based on engagement metrics.

## Key Insights
- **Length of Membership** is the most significant factor influencing customer spending, with a strong positive correlation. 💳
- **Time on App** also proves crucial, showing that mobile engagement plays a major role in driving higher customer spending. 📱✨
  
## Model Performance
The model's performance is evaluated with the following metrics:
- **Mean Absolute Error (MAE)**: 22.58
- **Root Mean Squared Error (RMSE)**: 27.54

These results demonstrate the model's accuracy and effectiveness in predicting customer spending.

## Tools & Libraries Used
- **Python**: For the overall implementation.
- **Pandas**: Data manipulation and exploration.
- **Matplotlib / Seaborn**: For data visualization.
- **Scikit-learn**: For model building and evaluation.
- **NumPy**: For numerical computations.

## Project Workflow

1. **Data Preprocessing**  
   The raw Kaggle dataset is cleaned and preprocessed, including handling missing values and normalizing numerical features.

2. **Exploratory Data Analysis (EDA)**  
   Various data visualizations are used to uncover patterns and relationships between the engagement metrics and spending.

3. **Model Building**  
   A regression model is built to predict **Yearly Amount Spent** based on the engagement features.

4. **Model Evaluation**  
   The model is evaluated using performance metrics such as **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)** to measure its accuracy.

5. **Final Insights**  
   Based on the model's findings, actionable insights are derived to understand which engagement metrics drive higher customer spending.


