# Bank-Risk-Analysis

The Bank Risk Analysis Dashboard is a data-driven, analytical Power BI + Python project designed to evaluate and classify customer risk profiles using demographic, financial, and behavioral attributes. The solution helps users identify high-risk customers, understand key factors influencing risk, and support crucial decisions for credit approval, loan structuring, and customer lifecycle management.

This end-to-end analysis is built for banking strategists, credit analysts, risk officers, product managers, and financial decision-makers who require a deeper understanding of customer income stability, savings patterns, credit utilization, tenure with the bank, nationality risk patterns, and financial behavior indicators that influence overall risk weighting.

Source
Customer dataset from a banking case study containing detailed information on demographics (age, gender, nationality), financial attributes (income, deposits, loans, savings, card balances), loyalty classification, tenure with the bank, and risk weighting segments. A total of 4,000+ customer records were processed using MySQL, Python (EDA), and Power BI.

Key Technologies Used
• Python (Pandas, NumPy, Matplotlib, Seaborn)
• MySQL Database
• Jupyter Notebook
• Power BI Desktop
• File Formats: .ipynb, .pbix, .png

Problem
Banks need to strengthen their credit risk evaluation processes to minimize loan defaults, classify customer risk efficiently, and identify behavioral trends that influence probability of repayment.

Goal of the Bank Risk Analysis Dashboard & EDA Pipeline
• Classify customers into low, medium, and high-risk segments.
• Understand how income, tenure, nationality, occupation, and financial attributes influence risk.
• Support credit decision systems for loan approvals and risk-based pricing.
• Build a clear understanding of customer behavior patterns that drive risk weighting changes.
• Create a visual risk monitoring dashboard.

Key Components of the Analysis

a) MySQL → Jupyter Notebook Integration
Connected Jupyter Notebook to the MySQL banking database using mysql.connector, extracted the entire customer table, and performed live data analysis.

b) Initial Data Profiling
Displayed data samples, descriptive statistics, and income distribution.

c) Income Band Segmentation
Created custom income groups (Low, Medium, High, Very High) and visualized income distribution.

d) Risk Weighting vs Estimated Income
Boxplot comparison showing how risk varies across income levels.

e) Categorical Attribute Distribution
Analyzed categories such as nationality, occupation, fee structure, and loyalty classification.

f) Risk by Nationality
Computed average risk for each nationality and visualized trends.

g) Customer Tenure Analysis
Calculated Years as Customer and compared tenure vs risk.

h) Correlation Heatmap
Compared financial variables such as income, savings, loans, deposits, and balances.

Business Impact
This risk analysis enables banks to:

• Identify and prioritize high-risk customers.
• Improve loan approval accuracy.
• Build safer credit strategies.
• Understand how demographics and financial behaviors affect risk.
• Reduce defaults through income and borrowing pattern analysis.
• Strengthen overall credit portfolio health.

