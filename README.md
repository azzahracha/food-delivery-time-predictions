# Food Delivery Time Analysis

Exploratory data analysis and interactive dashboard to identify the key factors 
driving food delivery time, using a dataset of 1,000 delivery orders.

## 📌 Project Background
Delivery time is one of the most critical factors affecting customer satisfaction 
in the food delivery industry. This project analyzes what drives delivery time 
and provides data-driven recommendations for operational improvement.

## ❓ Problem Statement
What factors most significantly affect food delivery time, and how can the 
company optimize its operations based on these findings?

## 📊 Dataset
- **Source:** Kaggle — Food Delivery Time dataset
- **Size:** 1,000 orders, 9 variables
- **Variables:** Distance (km), Weather, Traffic Level, Time of Day, Vehicle Type, 
  Preparation Time (min), Courier Experience (yrs), Delivery Time (min)
- **Data quality notes:** ~30 missing values in 4 categorical columns, handled during preprocessing

## 🔧 Tools & Methods
- **Python (Pandas, Matplotlib/Seaborn)** — data cleaning, EDA, correlation analysis
- **Power BI** — interactive dashboard for stakeholder exploration

## 🔍 Key Findings
| Factor | Correlation with Delivery Time | Insight |
|---|---|---|
| Distance | r = 0.78 | Strongest predictor; long-distance orders take ~2x longer than short ones |
| Weather | — | Rainy/Snowy conditions add 10–15 min on average vs Clear weather |
| Traffic Level | — | High traffic adds ~12 min vs Low traffic |
| Preparation Time | r = 0.31 | Moderate effect on total delivery time |
| Courier Experience | r = -0.09 | Minimal impact on delivery speed |
| Vehicle Type | — | No significant difference across Bike/Car/Scooter |

## 💡 Business Recommendations
1. Prioritize courier allocation on long-distance routes
2. Prepare weather-contingency protocols (buffer time / incentives)
3. Enable real-time rerouting during high-traffic periods
4. Improve kitchen/restaurant prep efficiency for slow partners
5. Keep vehicle allocation flexible across all types

## 📁 Repository Structure
