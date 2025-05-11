# Y.Afisha – Marketing Performance and Customer Behavior Analysis

This project was completed as part of an internship at the analytics department of Y.Afisha, a digital event platform. The main objective is to help the company optimize its marketing expenses by analyzing how users interact with the product, when they start purchasing, and how much revenue they generate over time.

🧾 Project Description

Using server logs, order data, and marketing spending records from January 2017 to December 2018, this analysis explores:

User behavior: how and when users interact with the platform

Conversion patterns: how long it takes for users to make their first purchase

Customer value: how much revenue each user generates (LTV)

Marketing effectiveness: which channels deliver the best ROI

The final goal is to recommend where and how much to invest in marketing based on data-driven insights.

💡 Objectives

Understand user engagement and retention

Analyze the conversion funnel and revenue patterns

Evaluate marketing efficiency per source and over time

Provide actionable marketing recommendations based on ROI and customer acquisition cost

📦 Datasets

Three datasets were used in this project:

visits_log_us.csv: Server logs containing session-level data

orders_log_us.csv: Purchase information, including user IDs and revenue

costs_us.csv: Marketing costs per day and ad source

Dataset Descriptions
visits
uid: unique user ID

device: device used (e.g., mobile, desktop)

start_ts: session start timestamp

end_ts: session end timestamp

source_id: marketing source ID

orders
uid: unique user ID

buy_ts: order timestamp

revenue: revenue from the purchase

costs
source_id: marketing source ID

dt: date of expense

costs: amount spent on that source and day

⚙️ Project Steps

1. Data Preparation
Data loading and optimization

Type conversion for timestamps and categories

Missing value handling and data consistency checks

2. Metric Calculation & Analysis
Product Analytics
Daily, weekly, and monthly active users (DAU, WAU, MAU)

Sessions per user per day

Session length distribution

User retention rates

Sales & Revenue
Time from registration to first purchase (conversion delay)

Number of purchases per user over time

Average purchase value

Lifetime Value (LTV) per cohort

Marketing
Total marketing spend per channel and over time

Customer Acquisition Cost (CAC)

Return on Investment (ROI) per channel

3. Visualization
Cohort analysis charts (conversion over time)

Session and retention heatmaps

Revenue trends by source and device

ROI comparison across marketing channels

📊 Tools & Libraries
pandas, numpy – data manipulation

matplotlib, seaborn, plotly – data visualization

datetime – time analysis

scipy.stats – hypothesis testing

📁 Project Structure

kotlin
Copiar
Editar
📦 y.afisha-marketing-analysis
├── 📁 data/
│   ├── visits_log_us.csv
│   ├── orders_log_us.csv
│   └── costs_us.csv
├── 📄 README.md
└── 📄 y_afisha_analysis.ipynb

✅ Results & Recommendations

Identified top-performing marketing channels based on ROI and CAC

Observed differences in conversion rates by device and ad source

Defined the break-even point for most channels and the typical conversion lag

Suggested increased investment in high-performing channels and optimization of low-conversion funnels

📌 Project Status

🟢 Completed – All steps of the project were conducted in a Jupyter Notebook, with analysis, visualizations, and strategic conclusions ready to guide marketing investment decisions.
