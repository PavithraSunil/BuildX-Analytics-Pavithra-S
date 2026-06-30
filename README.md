# BuildX-Analytics-Pavithra-S

# 🌍 Air Quality Analysis Dashboard using Power BI

## 📌 Project Overview

This project presents an interactive **Air Quality Dashboard** built using **Microsoft Power BI**. The dashboard analyzes air pollution indicators such as AQI, PM2.5, PM10, NO₂, SO₂, CO, and O₃ to provide meaningful insights into air quality trends and pollutant patterns.

The objective of this project is to transform raw air quality data into an easy-to-understand and visually appealing business intelligence dashboard.

---

## 📂 Dataset

The dataset contains air quality measurements with the following key fields:

* Date
* Station ID
* AQI (Air Quality Index)
* AQI Bucket (Category)
* PM2.5
* PM10
* NO₂
* SO₂
* CO
* O₃
* Year
* Month
* Day of Week

---

## 🎯 Project Requirements

This dashboard satisfies the following requirements:

* ✅ Minimum 6 visuals
* ✅ Minimum 2 report pages
* ✅ More than 4 different visual types
* ✅ One DAX Calculated Column
* ✅ One DAX Measure
* ✅ At least one Card visual
* ✅ At least one Slicer
* ✅ At least one Page-Level Filter
* ✅ Key Insights section with numerical business insights
* ✅ Professional layout with consistent colours
* ✅ Meaningful titles for every visual

---

# 📊 Dashboard Pages

## Page 1 – Air Quality Overview

### Visuals

* Card: Average AQI
* Card: Highest AQI Recorded
* Line Chart: AQI Trend Over Time
* Donut Chart: Distribution of AQI Categories
* Column Chart: Average PM2.5 by Month
* Slicer: Year / AQI Category

### Purpose

Provides a high-level overview of air quality conditions and trends.

---

## Page 2 – Pollutant Analysis

### Visuals

* Clustered Column Chart: Average AQI by Day of Week
* Scatter Plot: PM2.5 vs AQI
* Table: Daily Air Quality Details
* Page-Level Filter: AQI Category
* Key Insights Section

### Purpose

Analyzes pollutant behaviour and relationships between different air quality indicators.

---

# 🧮 DAX Calculations

## Calculated Column

```DAX
AQI Status =
IF(
    [AQI] > 200,
    "Poor",
    "Good"
)
```

## Measure

```DAX
Average AQI =
AVERAGE([AQI])
```

---

# 📈 Key Business Insights

Examples of insights generated from the dashboard:

* Highest AQI recorded during the observed period.
* Seasonal variation in PM2.5 levels.
* Distribution of air quality categories across the dataset.
* Relationship between PM2.5 concentration and AQI.

---

# 🛠 Tools Used

* Microsoft Power BI Desktop
* DAX (Data Analysis Expressions)
* CSV Dataset
* Data Visualization Techniques

---

# 📁 Repository Structure

```text
├── data/
│   └── cleaned_dataset.csv
├── dashboard/
│   └── dashboard.pbix
├── screenshots/
│   ├── page1.png
│   └── page2.png
├── README.md
```

---

# 🚀 How to Run the Project

1. Clone the repository.

```bash
git clone https://github.com/your-username/air-quality-powerbi-dashboard.git
```

2. Open `dashboard.pbix` using Power BI Desktop.

3. Refresh the dataset if required.

4. Explore the interactive dashboard.

---

# 📷 Dashboard Preview

Add screenshots of your dashboard here after completing the project.

---

# 📚 Learning Outcomes

This project demonstrates:

* Data cleaning and transformation
* Creating interactive dashboards
* Building DAX calculations
* Designing professional reports
* Extracting business insights from environmental data

---

## 👨‍💻 Author

**Your Name**

Power BI Beginner Project – Air Quality Analysis Dashboard
