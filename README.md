🧼 Soap ROI Analysis – Tamil Nadu (Power BI Project)
📊 Overview
This Power BI project analyzes the Return on Investment (ROI) for launching a Soap product in various Indian states, with a particular focus on Tamil Nadu. The objective is to identify the most promising state for product launch based on marketing efficiency and revenue returns.

🎯 Business Goal
To evaluate which Indian state offers the best marketing ROI for launching a soap product and to recommend whether Tamil Nadu is a viable market for high returns.

🧩 Dataset Summary
The dataset includes the following columns:

State

Year

Product (focused on 'Soap')

Revenue_INR_Lakhs

Marketing_Spend_INR_Lakhs

📈 Key Metrics Used
Total Revenue

Total Marketing Spend

ROI (%) calculated using:

DAX
Copy
Edit
ROI = 
((SUM(Revenue_INR_Lakhs) - SUM(Marketing_Spend_INR_Lakhs)) 
/ SUM(Marketing_Spend_INR_Lakhs)) * 100
📌 Insights
Tamil Nadu has one of the highest ROI values for Soap, indicating efficient marketing.

However, year-wise ROI trend in Tamil Nadu is inconsistent, suggesting short-term gains but potential long-term instability.

Comparing ROI across states and years helps prioritize markets that are both profitable and stable.

📊 Visuals in Dashboard
Bar Chart: ROI by State

Line Chart: ROI by Year per State

KPI Cards: Total Revenue, Marketing Spend, ROI

Filter Panels: Product Type, Year, and State

🧠 Recommendation
Tamil Nadu is a profitable region to launch the soap product, especially for short-term or limited campaigns. For long-term investments, monitor ROI trends over time or consider diversifying into more stable markets.

🛠 Tools Used
Power BI (Desktop)

Power Query (for cleaning data)

DAX (for custom calculations)

Excel (source data preparation)
