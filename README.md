# Online Advertising Performance Analysis
---
# Project Overview
This project provides an in-depth analysis of online advertising campaign performance from April to June 2020. Using a data-driven approach, we transform raw advertising data into a set of actionable insights and strategic recommendations to optimize campaign efficiency and improve Return on Investment (ROI).
---
# 🎯 Mission
Our primary goal is to provide a clear, evidence-based strategy for future advertising initiatives by:

1. Increasing Efficiency and ROI: Focusing resources on the most impactful ad combinations and placements. 

2. Enabling Targeted Efforts: Identifying which user segments, banner sizes, and placements are most effective.

3. Gaining a Deeper Understanding: Translating campaign data into a clear, actionable plan.
---

# 📊 Key Findings
Our analysis uncovered several critical insights that can significantly impact future ad performance:

1. User Engagement is Key: The 'High' engagement user segment is the most valuable, contributing almost 80% of all revenue.

2. Top-Performing Creatives: Banner sizes 240x400 and 728x90 consistently drive the highest volume of clicks.

3. Peak Performance Days: Performance metrics such as clicks and conversion rates (CVR) are strongest from Tuesday to Thursday.

4. Synergy in Combinations: A custom "Synergy Score" identified high-potential ad combinations, such as the 300x250 banner on the 'ghi' placement, which delivers exceptional ROAS.

5. Simulated Sales Uplift: A budget reallocation simulation showed that shifting just 10% of the budget from the worst to the best-performing combinations could lead to a sales uplift of 11.19%, representing a gain of over $3.6 million.
---

# 🛠️ Technical Approach
The analysis was performed using Python and key data science libraries. The workflow followed a disciplined, multi-step process:

1. Data Cleaning: Ensured data integrity by handling missing values and standardizing data types.

2. KPI Engineering: Computed critical Key Performance Indicators (KPIs) such as CTR, CVR, ROAS, and CPC to enable a deeper analysis.

3. Exploratory Data Analysis (EDA): Utilized visualizations to uncover trends and patterns in the data.

4. Correlation Analysis: Identified statistical relationships between key variables like cost and revenue.

5. Custom Modeling: Developed a custom Synergy Score to rank ad combinations based on their potential for return.

6. Simulation: Ran a budget reallocation simulation to quantify the financial impact of the strategic recommendations.
----

# 📂 Project Files
This repository contains the following key files:

1. Advertising Analysis Notebook.ipynb: The primary Jupyter Notebook containing the full analysis, code, and visualizations.

2. Advertising_Performance_Report.pdf: A comprehensive PDF report summarizing the project's findings and recommendations.

3. Online Advertising Performance Analysis.pptx: A PowerPoint presentation of the key insights, designed for business stakeholders.
----
# 🤝 How to Use
To run the analysis yourself, follow these steps:

Clone this repository:

git clone [https://github.com/your-username/your-project-name.git](https://github.com/your-username/your-project-name.git)

Navigate to the project directory.

Ensure you have a Python environment set up with the necessary libraries (e.g., pandas, numpy, matplotlib, seaborn). A requirements.txt file is coming soon!

Open and run the Advertising Analysis Notebook.ipynb to reproduce the analysis.

# 🧠 Future Work
A/B Testing: Validate the high-potential ad combinations identified by the Synergy Score with live A/B tests.

Predictive Modeling: Develop a predictive model to forecast ROAS based on campaign features.

Interactive Dashboard: Create a web-based dashboard for marketing teams to explore the data dynamically.
