# 📊 Profit Analysis 

# Project Overview
This project analyzes how R&D Spend, Administration Spend, and Marketing Spend affect company Profit using Multiple Linear Regression in Excel and visualizes the results with Tableau Dashboards.  

The dataset contains financial details of 50 startups across New York, California, and Florida.

# Objectives
- Perform regression analysis to identify which factors impact Profit.
- Predict Profit for new input values.
- Create Tableau dashboards to visualize Profit trends and provide business insights.
- Recommend strategies for maximizing profitability.

# Dataset Description
- Records: 50 startups  
- Features:
       R&D Spending
       Administration Spending
       Marketing Spending
       State
       Profit

# Tools & Technologies
- Excel   → Data Cleaning, Regression, Prediction  
- Tableau → Visualization, Dashboards  
  
# Methodology
# 1. Data Preparation
- Cleaned dataset in Excel
- Structured data for analysis

# 2. Regression Analysis (Excel)
- Dependent Variable → Profit  
- Independent Variables → R&D Spend, Administration, Marketing Spend  
- Extracted *coefficients & intercept* for prediction formula  

# 3. Profit Prediction(Excel)
Formula used:

Profit = Intercept + (Coeff_R&D*R&D_spend) + (Coeff_Admin*Administration_spend) + (Coeff_Marketing*Marketing_spend)

Predicted profit for new inputs using regression output.

# 4. Tableau Visualization
- Profit by State → Bar Chart  
- R&D vs Profit → Scatter Plot with Trend Line  
- Marketing vs Profit → Scatter Plot with Trend Line  
- Profit Contribution by State → Treemap  
- KPI Cards → Total Profit, Avg Profit, Max Profit  

# Insights
- R&D Spending is the most important driver of Profit.  
- Administration Spending shows very weak relation with Profit.  
- Marketing Spend has a moderate impact.  
- Some states (e.g., California) contribute higher average profit.  

# Recommendations
- Increase investment in R&D for sustainable profit growth.  
- Optimize Marketing strategies to get better ROI.  
- Control Administration overheads as they have minimal impact.  
- Focus on high-performing states for expansion.  




