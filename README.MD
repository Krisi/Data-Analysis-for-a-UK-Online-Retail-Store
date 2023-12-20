# Data Analysis for a UK Online Retail Store
## Project Description
This is my data analytics project exploring sales in a UK online retail store. All relevant files (the dataset, the Jupyter notebook, the README, and output files) are all contained within the same project directory. This makes the project more portable and manageable.In addition Python code was modified to utilize relative file paths when reading in data and writing output files. By opting for relative paths instead of absolute paths, the project is more portable and can be run by others on different machines without needing to adjust the file paths
## Overview
This Python script performs comprehensive data analysis on a retail and Consumer Price Index (CPI) dataset. By cleaning, merging, statistically analyzing, and visualizing the data, the script provides valuable insights about sales volume, reveals revenue rankings for different items, and explores relationships between variables via correlation and visualization methods. It uncovers average pricing of top-selling items and infers potential revenue-driving strategies adopted by the retail business..
## Objective:
Operating in an intensely competitive online retail market requires data-driven decision making. The data analysis applied to a UK retail store, aims to address the following insights:
- Identify key customers based on their buying behavior and purchase volumes, enabling targeted sales and marketing.
- Understand sales patterns to accurately forecast future sales trends, which is crucial for planning and resource allocation.
- Utilize return patterns to adeptly manage inventory and ensure stock levels align effectively with demand.
## Libraries Used:
- pandas: A Python library providing easy-to-use data structures like DataFrames for efficient data manipulation. It’s used in this project to load data from Excel files and perform data manipulation.- numpy: A library used for mathematical computations on multi-dimensional arrays and matrices. It's utilized for operations on numeric data.
- matplotlib.pyplot and matplotlib.patches: Libraries used for creating static, animated and interactive visualizations in Python.
- seaborn: An efficient plotting library used for creating informative and attractive statistical graphics in python.
## Methodology:
The workflow can be described as follows:
- Retail and CPI data are loaded from Excel files using utils in pandas providing efficient data handling.
- Clean up procedures are employed to ensure data integrity by removing duplicates, renaming ambiguous columns, and refining metadata. 
- The scrubbed datasets based on 'Year', their common attribute, are merged to form a unified DataFrame, leading to cohesive analysis. ![Data Cleanup Process Ouput](https://github.com/Krisi/Data-Analysis-for-a-UK-Online-Retail-Store/blob/master/Datacleanup.png)
- Descriptive analysis is performed using the unified DataFrame to provide statistical measures like mean, standard deviation, median, quartiles and correlation, offering insights into the central tendency and dispersion characteristics of the numerical variables.
- The correlations between 'CPI' and 'Quantity' variables are explicitly computed, which reveal focused insights.
- A summary of unique items is generated from the retail data using the 'Description' column, providing valuable information about the variety of items.
- The top 10 high-selling items are identified based on analysed 'Quantity' sold and revenue generated attributes.
- Composite scores are assigned to each item, leveraging a weighted sum of their normalized Quantity and Revenue values, acting as unified item rankings.
- Items are segregated into different price ranges based on their average price percentiles, offering nuanced pricing insights.
- After calculating the average pricing of top-selling items, results are compared with the store's average price.
- Key customers are identified using the 'Customer ID' attribute and tracking their buying quantities and overall spending.
- Outspread and skewness of quantity purchased and revenues are visualized leveraging matplotlib's box plot functions.
- Revenue fluctuations over time are identified by calculating daily and projecting them through line plots to observe trends.
- Empirical strategies are employed to detect outlier days (significantly high or low revenues) for further investigation.
## Use Cases:
The script provides a comprehensive analysis of retail sales, catering to a variety of needs including retail businesses aiming for competent strategic decision-making, economize, and data analysts seeking to improve their understanding of retail markets. It navigates through raw data to extract meaningful information, delivers results through quantified operational metrics, visually portrays results for improved comprehension, and offers actionable insights for effective decision-making.
## Potential Applications
- Employ sophisticated measures for customer segmentation. Recognize valuable customers based on their contribution to sales and revenue, designing targeted marketing strategies and personalized experience for improved customer retention.
- Forecast future sales based on calculated daily and monthly revenues and observed trends, planning for future market scenarios.
- Develop effective product bundling strategies and personalized product recommendations leveraging the results of the market basket analysis.
- Enhance inventory management by foreseeing potential financial risks from product returns and maintaining optimal inventory levels to mitigate them.
## Future Analysis:
Potential future analysis that can provide further strategic insights include:
- Predictive Analysis: Utilize machine learning algorithms in conjunction with available sales data to forecast potential sales and revenues. This would aid businesses to prepare for future market demands.
- Customer Segmentation and Profiling: Perform an in-depth analysis of customer segments considering multiple attributes like demographics, behaviour, and transaction history. Profiling these segments would provide insights to fine-tune marketing and service strategies.
- Sentiment Analysis: Analyse available customer reviews and feedback for sentiment, providing insights on customer satisfaction and product performance.
- Churn Analysis: Identify and analyse customers who are at risk of churning. Develop strategies to retain these customers by understanding their purchase behaviour and preferences.
- Product Affinity and Recommendation: Use market basket analysis to understand which products are often purchased together, and develop a recommendation system to increase sales.
- Geographical Revenue Analysis: Analyse revenue contributions based on regions to identify potential markets for expansion or to devise region-specific marketing strategies.
Thank you for going through this README file to understand the workings of this analysis. The final deliverable is a set of actionable insights that can drive improved decision-making processes. For any further inquiries or suggestions, feel free to reach out
