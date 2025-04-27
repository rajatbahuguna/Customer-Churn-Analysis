Customer Churn Analysis

Customer churn analysis to identify factors influencing customer retention using data exploration and visualization.

Project Objective

Goal: The goal of this project is to analyze customer churn patterns in a telecommunications dataset to identify key factors associated with customers discontinuing services, with a focus on data cleaning, exploration, and visualization.





Perform data cleaning to ensure dataset quality.



Conduct exploratory data analysis to understand customer characteristics and churn behavior.



Visualize relationships between features and churn to uncover actionable insights.

Analysis Steps





Data Loading and Cleaning:





Loaded the dataset (Customer Churn.csv) using pandas.



Replaced blank TotalCharges values with 0 and converted to float.



Verified no missing values or duplicates.



Transformed SeniorCitizen from 0/1 to "No"/"Yes" for clarity.



Exploratory Data Analysis:





Examined data structure and summary statistics using df.info() and df.describe().



Analyzed churn distribution by payment method using a seaborn countplot.



Visualization:





Created a countplot to show churn by payment method, highlighting higher churn among customers using electronic checks.

Conclusion

The analysis revealed that customers using Electronic Check as a payment method are more likely to churn compared to those using other methods (e.g., Bank Transfer, Credit Card, Mailed Check). This suggests that businesses could investigate issues related to electronic check payments or encourage alternative payment methods to improve retention. The dataset was clean and well-structured, enabling reliable insights. Future work could include additional visualizations, statistical tests, or predictive modeling to further understand and predict churn behavior.
