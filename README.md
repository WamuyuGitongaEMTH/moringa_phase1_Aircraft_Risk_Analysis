# Aviation Accident Risk Dashboard

A data-driven analysis of historical aviation accidents (1962–2023), aimed at helping stakeholders identify low-risk aircraft makes and models for acquisition.

---

## Overview

This project explores trends in aviation accident data from the National Transportation Safety Board to support strategic decision-making for a company entering the aviation industry.

The outcome is an interactive dashboard, data analysis, and final business recommendations to guide safe aircraft procurement.

---

## Business Understanding

**Stakeholder:**  
A new aviation division within a larger company evaluating which aircraft to acquire.

**Key Business Questions:**
- Which aircraft makes and models have the highest accident severity?
- How does weather or phase of flight influence accident risk?
- What aircraft should be considered low-risk for acquisition?

---

##  Data Understanding and Analysis

### 📦 Data Source:
- National Transportation Safety Board (NTSB) Aviation Accident Database  
- (https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)

### Data Summary:
- 40,000+ records from 1962–2023
- Features: Aircraft make/model, location, date, injury severity, weather, phase of flight

###  Visualizations:
#### 1. **Bar Chart:** Top 15 Aircraft Models by Risk Level  
Shows severity distribution per model using color-coded risk levels.

#### 2. **Heatmap:** Aircraft Make vs. Weather Condition  
Highlights accident trends by manufacturer under VMC/IMC conditions.

#### 3. **Line Chart:** Accidents Over Time  
Tracks year-by-year trends and highlights spikes/declines.

>  Explore the dashboard: [Click here to view it on Tableau Public](https://public.tableau.com/app/profile/wamuyu.gitonga/viz/AviationAccidentRiskAnalysis_17459584453790/Dashboard1?publish=yes)

---

## Conclusion

### Key Findings:
- **Cessna 172** and **Beech A36** are high-risk models with a large number of fatal incidents.
- **Piper PA-28** shows moderate frequency but better survivability.
- Weather (IMC) and flight phase (landing/takeoff) are critical risk multipliers.

### Final Recommendations:
To safely enter the aviation space:

1. **Avoid Cessna aircraft** in your entry fleet — especially 172 — due to their disproportionate fatal involvement.
2. **Select Piper PA-28** for general aviation; it's more survivable and broadly operated under VMC.
3. For commercial aspirations, **Boeing models show excellent safety** profiles and are well-regulated.
4. **Build robust training and weather policy frameworks** — especially for models with higher risk during takeoff/landing.

---

## Project Structure

- `data/` – Cleaned dataset used for analysis
- `presentation/` – Final presentation in PDF format
- `dashboard/` – Screenshots or links related to Tableau dashboard
- jupyter notebook

---

##  Technologies Used

- **Python, Pandas, Seaborn, Matplotlib**
- **Tableau (Interactive Dashboard)**
- **Jupyter Notebook**
- **Git/GitHub**

---

##  Commit History & Collaboration
 Clear, frequent commits documenting progress   Exploratory notebooks included   Git best practices followed (e.g., .gitignore)


