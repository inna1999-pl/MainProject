# Coffee Sales Analysis

## Project Overview
This project analyzes coffee shop sales data from Kaggle to identify customer purchasing patterns, key revenue drivers, and business growth opportunities. The analysis combines exploratory data analysis (EDA), statistical testing, and machine learning techniques to answer business-oriented questions related to customer spending, product performance, seasonality, and sales trends.

The project aims to transform raw transaction data into actionable business insights that can support decision-making in areas such as inventory management, staffing, marketing, and sales optimization.
## Data Description
Source: [Coffee Sales Dataset from Kaggle.](https://www.kaggle.com/datasets/rifatalam3/coffee-revenue-dataset)

The dataset contains transaction-level sales data from a coffee shop, including purchase date and time, coffee type, and transaction revenue.

Data preparation included:

- Converting the date column from object to datetime64[ns].
- Exploring unique values of categorical variables.
- Detecting and evaluating potential outliers.
- Creating additional time-based feature such as quarter.
## Analysis Methods
The following analytical methods were applied:

- Exploratory Data Analysis (EDA) to investigate transaction value distribution, customer spending behavior, product performance, and revenue trends.
- Data visualization using histogram, bar chart, Pareto chart, line plot, boxplot, point plot, violin plot, and correlation heatmap.
- Descriptive statistical analysis to evaluate average transaction value and revenue distribution.
- Outlier detection to identify unusual observations and assess data quality.
- Time-based analysis to explore hourly, daily, monthly, quarterly, and seasonal sales patterns.
- Correlation analysis to examine relationships between revenue and time-related variables.
- Hypothesis testing (A/B testing) to determine whether average revenue differs between weekdays and weekends.
- Random Forest Classification to predict whether a transaction would be classified as a high-revenue transaction.
- Feature importance analysis to identify the factors with the strongest influence on transaction profitability.
## Tools and Technologies
The project was developed using the Python data analytics ecosystem. Data preprocessing and manipulation were performed with Pandas and NumPy. Visualizations were created using Matplotlib and Seaborn. Statistical analysis and hypothesis testing were used to validate business assumptions. A Random Forest Classification model was implemented with Scikit-learn to predict high-revenue transactions and identify the most influential factors affecting sales performance.
## Key Findings and Recommendations
### Key Findings
- The average transaction value was approximately 31.65.
- Most transactions were concentrated in the 35–36 revenue range.
- Americano with Milk, Latte, Americano, and Cappuccino generated the majority of sales, confirming the Pareto principle.
- Revenue peaked around 10:00 AM and remained high throughout the morning and afternoon.
- Sales showed seasonality, with the strongest performance in Q2 (April–June) and weaker results in Q3 (July–September).
- Purchase time had a stronger influence on revenue than weekday or seasonal factors.
- No statistically significant difference was found between average revenue on weekdays and weekends.
- The Random Forest model achieved 96.7% accuracy in predicting high-revenue transactions.
- Coffee type, month, and purchase hour were identified as the most important factors influencing high-revenue sales.
### Business Recommendations
- Focus marketing efforts on the most profitable coffee products, particularly Americano with Milk, Latte, Americano, and Cappuccino.
- Increase staffing levels and inventory during peak demand hours, especially between 08:00–11:00 and 15:00–17:00.
- Implement upselling strategies through desserts, premium drink sizes, syrups, and add-ons to increase average transaction value.
- Launch seasonal campaigns and cold beverage promotions during lower-performing summer months.
- Optimize staff scheduling and inventory management based on hourly demand patterns.
- Use machine learning insights to identify high-value transactions and improve marketing effectiveness.
