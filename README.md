# Aircraf Risk analysis

#  Aircraft Risk Analysis for Business Expansion

## 📌 Project Overview
This project analyzes historical aviation accident data to identify **low-risk aircraft makes and models**. The goal is to support a company planning to expand into **commercial and private aviation operations** by providing **data-driven, actionable insights** on aircraft safety.

The analysis focuses on injury outcomes as a proxy for operational risk and translates findings into **business recommendations** and an **interactive Tableau dashboard**.

---

##  Business Understanding
The company aims to diversify its portfolio by purchasing and operating aircraft but lacks expertise in aviation risk.

### Business Questions
- Which aircraft makes and models have the **lowest injury risk**?
- How can historical accident data inform **safer aircraft purchase decisions**?
- What actionable insights can leadership use to guide expansion into aviation?

---

##  Data Understanding
- **Dataset:** Aviation accident data (`AviationData.csv`)
- **Source:** Historical aviation safety records
- **Key Fields:**
  - Aircraft Make & Model
  - Fatal, Serious, and Minor Injuries
  
### Data Preparation
- Cleaned missing injury values
- Removed records with missing aircraft identifiers
- Created a new metric: **Total Injuries**
##  Data Analysis
### Risk Metric
- **Average Injuries per Accident**
- Aircraft with low average injuries and sufficient accident history were classified as **low-risk**

![average_injuries_per_accident](images\Screenshot 2025-12-16 115727.png)

### Reliability Filter
- Only aircraft with **20 or more recorded accidents** were included to ensure statistical validity.

---
### Trend analysis over time
Injuries reduced by number of years

![trend_analysis_over_time](images\Screenshot 2025-12-16 120006.png)

## Key Findings
- **General aviation aircraft** show consistently lower injury risk
- Aircraft with long operational histories outperform rare or experimental models
- Injury types (fatal, serious, minor) are strongly correlated, validating the use of total injuries as a risk metric

### Lowest-Risk Aircraft Manufacturers
- Boeing 737- 800
- Cessna A185
-Grumman G1648

---

##  Recommendations
- **Aircraft Acquisition Strategy**

Prioritize low-risk aircraft makes and models with:

 - Low average injuries per accident like the Boeing 737-800 and Grumman G1640.


 **Type and numberof Engines**
  - Opt for aircraft with 2 or more engines for low fatality rate.The Geared Turbofan, LR and Electric have low fatality rate which is also recommended.

  **Trend Analysis**
  Choose aircraft models that are recent has they have low injury rate as trend shows decreasing accidents over time

---

---

##  Tableau Dashboard
An interactive Tableau dashboard was created to allow stakeholders to:
- Filter aircraft by manufacturer
- Compare injury risk across makes 
- Explore which aircraft category has least injuries

**Key Interactive Features:**
- Filters for Make and Accident Count
- Tooltips with detailed aircraft metrics
- Dynamic ranking of lowest-risk aircraft

---

## 🛠 Tools & Technologies
- **Python:** pandas, matplotlib
- **Jupyter Notebook:** Data cleaning & analysis
- **Tableau Public/Desktop:** Interactive dashboard
- **GitHub:** Version control & project documentation

---

## 👩‍💼 Author
**Brenda Chepkemoi**  

