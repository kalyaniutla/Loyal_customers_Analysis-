# Loyal_customers_Analysis-
Project Title: Customer Lifetime Value Prediction Using Transactional Data
1. Introduction:
   
•	Objective: The project aims to predict the Customer Lifetime Value (CLV) using transactional data from an online retail dataset.
•	Language and Libraries Used: Python 3, Pandas, Lifetimes, Matplotlib, Seaborn.

2. Data Collection and Preprocessing:
•	Data Source: Online retail dataset obtained from .
•	Steps:
•	Data imported using Pandas.
•	Date format standardized.
•	Missing values in CustomerID column removed.
•	Records with non-negative quantity retained.
•	Total sales calculated.
![istockphoto-1693644309-1024x1024](https://github.com/kalyaniutla/Loyal_customers_Analysis-/assets/167401916/baad9132-8f7f-4a60-b688-1f6954659612)

3. Exploratory Data Analysis (EDA):
•	Insights:
•	Summary statistics and distribution of data explored.
•	Unique Customer IDs identified.
•	Histogram generated to visualize frequency of purchases.

4. Frequency/Recency Analysis:
•	Method: Utilized Lifetimes library to perform Frequency/Recency analysis.
•	Modeling: BetaGeoFitter model fitted to frequency, recency, and age data.
•	Visualizations: Frequency-recency matrix and probability alive matrix plotted.

5. Predictive Analytics:
•	Prediction: Estimated future transactions for a specified time horizon.
•	Visualization: Visualized the predicted number of transactions using a histogram.

6. Gamma-Gamma Model for CLV:
•	Method: Employed Gamma-Gamma Fitter from Lifetimes library to model monetary value.
•	Modeling: Fitted Gamma-Gamma model to frequency and monetary value data.

7. Customer Lifetime Value Calculation:
•	Calculation: CLV computed using fitted BG/NBD and Gamma-Gamma models.
•	Parameters: Time horizon set to 12 months with a discount rate of 0.01.

8. Conclusion:
•	Summary: Recap of project objectives, methodologies, and outcomes.
•	Insights: Insights gained from CLV analysis and implications for business strategy.

![istockphoto-1487132890-1024x1024](https://github.com/kalyaniutla/Loyal_customers_Analysis-/assets/167401916/af378233-0d9b-465c-97d6-6aea32bb25f1)


10. Future Work:
•	Enhancements: Suggestions for model refinement and extension.
•	Further Analysis: Areas for additional exploration to improve predictive accuracy.

11. References:
•	Credits: Acknowledgment of dataset source and libraries used.
•	Documentation: References for Lifetimes library and other resources.

