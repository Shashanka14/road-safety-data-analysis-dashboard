# Road Safety Data Analysis & Dashboard

## 📌 Project Overview
This project analyzes UK road accident data and presents actionable insights through a **Power BI dashboard**.  
The analysis aims to identify accident patterns, severity distribution, high-risk locations, and the influence of environmental factors on road safety.

The dataset underwent extensive **data cleaning, standardization, and deduplication** to ensure accurate reporting.  
The interactive dashboard allows stakeholders to explore accident trends by location, time, severity, weather, and road conditions.

---

## 🛠 Tools & Technologies
- **Power BI** – Dashboard creation, KPI tracking, and interactive visualizations  
- **Excel / CSV Processing** – Data preprocessing  
- **Data Cleaning Techniques** – Deduplication, label correction, normalization  

---

## 📊 Data Cleaning & Preprocessing
Steps performed:
1. **Deduplication** – Removed duplicate `Accident_Index` entries to ensure uniqueness.
2. **Label Standardization** – Corrected misspellings (e.g., "Fetal" → "Fatal").
3. **Normalization** – Unified values for fields like `Junction_Control` and handled missing data (`NULL` for unknown junction types).
4. **Value Corrections** – Fixed inconsistent category labels for better grouping and visualization.

---

## 📈 Key Findings
- **Total Casualties:** 418K  
- **Total Accidents:** ~308K  
- **Most Affected District:** Birmingham  
- **Accident Severity:**  
  - Slight injuries: ~263K  
  - Serious injuries: ~40K  
  - Fatal injuries: ~4K  

### Environmental Conditions
- Most accidents occurred in **fine weather + high visibility** and **dry road conditions** (208K+ cases).
- Hazardous conditions (snow, floods) caused fewer accidents but had **higher fatality ratios**.

### Junction & Traffic Control
- **Auto traffic signals** involved in ~48.7% of accidents.
- ~31.8% accidents occurred away from junctions.

### Time Trends
- Peak months: **October (28.4K)** & **November (29K)**.
- Lowest month: **February (21.9K)**.
- Most accident-prone day: **Friday (51K)**; least: **Sunday (34K)**.

---

## 💡 Insights & Recommendations
1. **Policy & Enforcement** – High accident counts in clear weather suggest driver behavior as a key cause; stricter junction enforcement needed.
2. **Awareness Campaigns** – Focus on Fridays, weekends, and festive months (Oct–Nov), even in good weather.
3. **Infrastructure** – Review junction designs at high-accident intersections; improve signage & add pre-warning systems.
4. **Emergency Readiness** – Prioritize quick response mechanisms in Birmingham.

---

## 📂 Repository Structure
