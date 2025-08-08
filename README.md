# Churn-Analysis-Prediction
This project is an end-to-end telecom churn analysis and prediction using interactive dashboards and machine learning. Visualizes churn trends, identifies at-risk customers, and provides key insights for targeted retention strategies.

## Key Technologies Used

- *Python* - The primary language for data analysis, processing, and predictive modeling.

- *Jupyter Notebook* - Interactive environment for step-by-step exploration, documentation, and sharing workflows.

- *Pandas & Numpy* - Reliable libraries for data manipulation, cleaning, transformation, and fast numerical computations.

- *Matplotlib & Seaborn* - Tools for designing visualizations, charts, and graphical summaries essential for communicating churn trends.

- *Scikit-learn* - Machine learning framework for preprocessing, model building, and evaluation.

- *Joblib* - Efficient model serialization: saves trained models to disk and loads them back for future predictions or deployment.

- *Openpyxl* - Library for reading and writing Excel (.xlsx) files, enabling direct integration with business data sources.

- ## Data Source Information

 The sample dataset illustrated here has been synthesized for demonstration purposes in the Customer Churn Analysis and Prediction Dashboard. It is designed to closely simulate real-world telecom operations and typical customer records, including churn status, account history, payment details, service usage, and demographic information.

The structure and fields in this synthetic data are inspired by attributes commonly maintained in telecom and subscription management systems, such as:

Customer demographics (ID, age, gender, marital status)

Account and contract details (tenure, contract type, payment method)

Service information (internet type, phone service, value-added services)

Usage patterns and monthly charges

Churn tracking (churn status, category, and reason)

This sample data enables comprehensive analysis and predictive modeling of customer churn, mirroring challenges faced in real-world subscription industries. It supports exploration of factors influencing churn as well as the development of machine learning solutions for customer retention.

## Features & Highlights

- *Comprehensive Churn Monitoring*

Track total customers, new joiners, churned customers, and churn rates across various demographics and account segments. Analyze month-over-month or tenure-based churn trends for deeper retention insights.

- *Demographic & Geographic Breakdown*

Visualize churn distribution by gender, age group, marital status, and by top states. Identify regions and population segments with higher churn risk to prioritize targeted interventions.

- *Tenure & Contract Analytics*

Analyze churn by tenure (months with company), contract type (month-to-month, one year, two year), and payment methods. Pinpoint customer cohorts and contractual arrangements most linked to attrition.

- *Service Impact Assessment*

Map churn rates against usage of key services: internet type, phone plans, streaming, online security, backup, and device protection. See how specific add-ons drive retention or increase churn likelihood.

- *Churn Attribution & Reasoning*

Break down total churn by category (Competitor, Attitude, Dissatisfaction, Price, Other) and explore primary reasons for customer departure. Use these insights to guide business strategy and improve customer satisfaction.

- *Predictive Churn Model*

Machine learning models (Random Forest, etc.) classify customers at risk of churning. Generate actionable lists of “Customers at Risk” including churner profiles—by state, age, tenure, payment method, and predicted probability.

- *Dynamic Filtering & Exploration*

Interactively filter dashboards by monthly charge range, marital status, contract type, and more. Drill down into granular views for detailed analysis of specific customer segments.

- *Key Performance Indicators (KPIs)*

Monitor KPIs such as total customers, new joiners, total churn, churn rate, and revenue at risk directly from the main dashboard.

- *Intuitive Visualizations*

Leverage pie charts, bar graphs, line plots, and interactive cards for data exploration. Easily toggle between summary and churn prediction for stakeholder presentations.

- *Secure & Shareable*

Project structure designed for easy sharing, reproducibility, and integration in team settings. Ready for future deployment as a web dashboard or integration with BI tools.

## Impacts

Highest Risk Segments

Customers over 50 years old and those with tenure above 24 months churn at higher rates (churn peaks at 31.1% and 27.5% respectively).

Month-to-month contract holders churn at a rate of 48.5%, much higher than annual or biennial contract types.

States like Jammu & Kashmir, Assam, and Jharkhand exhibit the highest churn, highlighting geographic targeting opportunities.

Service Influence

Use of Fiber Optic internet is associated with high churn (41.1%), suggesting either dissatisfaction or competitive offers in those regions.

Customers with certain service add-ons (like Device Protection Plans, Online Backup, Multiple Lines) show significantly higher churn percentages (e.g., Device Protection Plan holders churn at 71%).

Behavior & Payment

Customers using “Mailed Check” and “Bank Withdrawal” as payment methods are at higher risk (37.8% and 34.4% churn rates), compared to those using credit cards.

Churn is lowest among customers on two-year plans (2.7%) and those who pay by credit card (14.8%).

Churn Attribution

Most churns are attributed to competitors, with competitor-driven churn forming the largest share, followed by attitude and dissatisfaction reasons. This guides where product differentiation and customer engagement can be most impactful.

Predictive Model Insights

The dashboard’s machine learning outputs allow for actionable, individual-level intervention—teams can see which customers, by demographic and usage profile, are most at risk, supporting proactive outreach and tailored retention offers.

Overall, these insights enable the business to move from reactive reporting to proactive churn management—optimizing retention, boosting revenue, and guiding continuous service improvement
