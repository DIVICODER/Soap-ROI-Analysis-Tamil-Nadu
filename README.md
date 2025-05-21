# 🧼 Soap ROI Analysis – Tamil Nadu (Power BI Project)

## 📊 Overview
This Power BI project analyzes the **Return on Investment (ROI)** for launching a **soap product** across different Indian states. The focus is on evaluating the marketing efficiency in **Tamil Nadu**, helping identify whether it is a profitable region for a new product launch.

---

## 🎯 Business Goal
To determine which Indian state offers the **best ROI** for launching soap, and whether Tamil Nadu is a **strategic location** for high marketing returns.

---

## 🧩 Dataset Summary
The dataset includes the following fields:

- `State`
- `Year`
- `Product` (Soap-focused)
- `Revenue_INR_Lakhs`
- `Marketing_Spend_INR_Lakhs`

---

## 📈 Key Metric Used

**ROI Calculation (in DAX):**
```DAX
ROI = 
((SUM(Revenue_INR_Lakhs) - SUM(Marketing_Spend_INR_Lakhs)) 
/ SUM(Marketing_Spend_INR_Lakhs)) * 100
```

## 📌 Insights

- **Tamil Nadu has a high ROI for Soap**, suggesting efficient marketing spend.
- **ROI is inconsistent over the years in Tamil Nadu**, indicating short-term potential but **long-term volatility**.
- **Comparing ROI across other states** reveals alternatives that may offer **more stable long-term growth**.

---

## 📊 Visuals in the Dashboard

- **Bar Chart** – ROI by State  
- **Line Chart** – Year-wise ROI Trend  
- **KPI Cards** – Total Revenue, Marketing Spend, and ROI  
- **Slicers/Filters** – Product, State, and Year filters for drill-down analysis  

---

## 🧠 Final Recommendation

- Tamil Nadu is a **high-potential market** for launching Soap if the goal is **short-term ROI**.
- For **long-term campaigns**, further analysis of year-wise trends is recommended.
- Consider **diversifying into stable high-ROI states** to ensure consistent long-term marketing success.

---

## 🛠 Tools Used

- **Power BI Desktop** – For visualization and dashboard creation  
- **Power Query** – For data cleaning and transformation  
- **DAX** – For calculated metrics like ROI  
- **Excel** – For initial dataset preparation and structure  

