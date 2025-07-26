# Netflix-Churn-Dashboard
1.	**Project Title / Headline** :
   
   Netflix User Insights Dashboard: Behavior, Churn, and Revenue Analysis

2. **Purpose of this Project**:
   
  The goal of this dashboard is to help stakeholders identify key factors influencing customer retention and revenue. By analyzing metrics like churn rate by region, watch hours by age group, and payment method preferences, this tool supports data-driven decisions for improving user engagement and minimizing churn.
In this dataset:
churned = 0 means the customer has not churned
(i.e., they are still active/subscribed)
And:
churned = 1 means the customer has churned
(i.e., they left or unsubscribed)


3. **Tech Stack**:
   
The dashboard was built using the following tools and technologies:
a) **Power Bi** : For visualization
b) **SSMS** : For querying through the data and preparing the data.
c) **DAX (Data Analysis Expressions)** : Used for calculated measures, dynamic visuals, and conditional logic.

4.	**Data Source**:
   The data is imported from kaggle.
  	source : https://www.kaggle.com/datasets/abdulwadood11220/netflix-customer-churn-dataset

5. **Features**:
   
   1. **Business Problem**:
In the highly competitive OTT (Over-the-Top) streaming industry, customer churn is a critical challenge. Understanding why users cancel their subscriptions is essential for platforms like Netflix to optimize pricing, content, and user experience. This project tackles the issue of high churn rates and seeks to uncover the factors contributing to user retention or loss.

2.**Goal of the Dashboard**:
The goal is to provide a 360-degree view of customer churn by analyzing patterns across demographics, subscription types, watch behavior, payment methods, and revenue. The dashboard is designed to help stakeholders make data-driven decisions to reduce churn, enhance engagement, and maximize revenue.

3. **Walkthrough of Key Visuals & Impactful Insights**:
a) **KPI Cards**: Show total customers, churned customers, churn rate, total revenue, and active revenue at a glance.
Higher churn among users paying with gift cards or crypto suggests less committed subscribers — improving payment flexibility could help.

b) **Churn by Gender (Donut Chart)**: Highlights how churn varies among male, female, and other genders.
he 60+ age group shows higher watch hours but also significant churn — potential for age-specific content or loyalty perks.
c) **Churn by Region & Payment Method (Bar Charts)**: Reveal which areas and payment options have higher dropout rates.
Standard and Basic users show more churn compared to Premium — pricing strategies and feature enhancements could retain lower-tier subscribers.

d) **Watch Hours by Age Group (Bar Chart)**: Shows content consumption patterns across age segments.
Younger age groups (e.g., 18–30) tend to have higher average watch hours, indicating they are the most engaged viewers. In contrast, older age groups may watch less, potentially due to content preferences or usability issues.

e) **Avg. Monthly Fee vs Churned (Grouped Bars)**: Compares revenue behavior of retained vs churned users by subscription tier
Users on lower-priced plans (e.g., Basic) tend to churn more than Premium users. This ]indicates that budget-conscious users are less loyal, or that the lower plans offer insufficient value.

f) C**ustomer Segmentation by Genre and Gender (Stacked Bar)**: Highlights genre preferences and gender distribution.
Some genres (like Romance or Drama) are more popular among female users, while genres like Action or Sci-Fi skew toward male viewers.


6. **Dashboard Preview**:
   https://github.com/HinnaAkhlaque/Netflix-Churn-Dashboard/blob/main/Snapshot%20of%20dashboard.png
   

  	
