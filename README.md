Project Summary: Customer Segmentation, Cohort Analysis & Purchase Prediction

Objective:

To understand customer behavior over time, segment them using RFM metrics, and predict future purchases and spend using machine learning models (Random Forest & XGBoost).

Key Observations:

1.	Cohort Analysis:
	•	Customers were grouped by their first purchase month (cohort date).
	•	The analysis revealed how customer retention trends over time, showing a decline in repeat engagement as months progressed.
	•	Helpful in identifying strong acquisition months and periods where retention strategies could be improved.
 
 2.	RFM Analysis:
	•	Customers were scored based on Recency (how recently they purchased), Frequency (how often they purchase), and Monetary value (how much they spend).
	•	These scores helped us categorize customer value and behavior patterns.
	3.	Customer Segmentation (K-Means):
	•	K-Means clustering was applied to the RFM data to divide customers into segments.
	•	Each cluster represented a unique customer profile (e.g., loyal spenders, recent one-time buyers, dormant customers).
	•	Visualization of cluster sizes and labeling aided interpretation and targeting.
	4.	Purchase Prediction (BG/NBD):
	•	The BG/NBD model estimated future purchase frequency.
	•	A scatter plot of actual vs. predicted purchases showed the model’s ability to generalize reasonably well across different customer behaviors.
	5.	Monetary Prediction (ML Models):
	•	Both Random Forest and XGBoost models were trained to predict future customer spend using RFM features.
	•	Random Forest had slightly better accuracy, reflected in lower MAE and RMSE scores.
	•	Automatically generated bar graphs compared model performance without manual input of results.

Conclusions:
	•	Cohort trends highlight the importance of retention and suggest timing for re-engagement campaigns.
	•	RFM segmentation and clustering enable targeted marketing, customer prioritization, and personalized outreach.
	•	Predictive models offer a scalable way to forecast customer value, helping in budget allocation and strategic decision-making.
	•	Overall, this analysis builds a data-driven framework for understanding and optimizing customer lifecycle management.
