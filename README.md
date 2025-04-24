🛒 E-Commerce Return Rate Analysis Dashboard
This project analyzes and visualizes product return behavior in an e-commerce platform. It identifies patterns, user behavior, and key factors contributing to product returns using Power BI and Python (Logistic Regression).

📊 Power BI Dashboard Features
1. Overview Page
🔢 Total Orders

🔁 Total Returns

📈 Return Rate %
(Displayed using Card Visuals)

2. Return Trends Over Time
📅 Line chart showing return rate trend by Order_Date (monthly/yearly)

3. Return Reasons Breakdown
🥧 Pie/Donut chart showing the count of different return reasons

4. Return Rate by Location
🗺 Filled Map visual showing return rate per location

5. User Behavior Analysis
📊 Clustered Column Chart:

X-axis: User_Age groups (e.g., 18–25, 26–35)

Y-axis: Count of Returns

Color: User_Gender

6. Discount vs Return Rate
📈 Line or Column Chart showing relation between discount % and return rate

7. Additional Insights
📊 Correlation charts like:

Product Category vs Returns

Payment Method vs Returns

🧠 Predictive Analysis with Logistic Regression (Python)
Used Logistic Regression to predict product returns based on:

Discount applied

User age/gender

Product category

Shipping method

Order quantity

Model Accuracy Report

Accuracy Score

Confusion Matrix

Classification Report

🧩 Filters for Better Insights
📆 Date Range (Order_Date)

📦 Product Category

🏙 Location

🚻 User Gender

📎 Files Included
dashboard.pbix – Power BI file

return_model.ipynb – Python notebook for logistic regression


