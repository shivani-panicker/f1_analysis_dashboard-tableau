# 🏎️ Formula 1 Data Analysis Dashboard

An end-to-end data analytics project analyzing Formula 1 race data using **Excel, Power Query, and Tableau**.  
The project explores driver, constructor, and circuit performance across multiple decades of Formula 1 racing.

---

## 📊 Dataset

**Source:** Kaggle – Formula 1 World Championship Dataset  
**Coverage:** 1950 – 2020

The dataset includes historical data on:

- Drivers
- Constructors
- Circuits
- Race results
- Lap times
- Seasons

Multiple CSV files were combined and transformed into a structured dataset for analysis.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- **Power Query**
- **Tableau**
- Data Cleaning & Transformation
- Data Visualization

---

## 🔧 Data Preparation

- Consolidated multiple CSV files into a single Excel workbook.
- Cleaned and transformed data using **Power Query**:
  - Corrected data types
  - Handled missing values
  - Standardized column formats
- Merged relational tables using ID keys to create a **26,759-row master dataset**.
- Performed feature engineering including:
  - Win, Podium, and DNF indicators
  - Positions gained/lost
  - Driver age at race
  - Lap time conversion to seconds

---

## 📈 Dashboard & Visualizations

The dataset was connected to **Tableau** to create an interactive dashboard including:

- **Top N Drivers Chart** – compares wins, podiums, and points with a dynamic parameter.
- **Constructor Performance Chart** – dual-axis chart showing wins and total points.
- **Circuit Map** – geographic visualization of circuits with race frequency.
- **Year-over-Year Driver Performance** – shows point changes and percentage difference.
- **KPI Cards** displaying:
  - Total races
  - Total laps
  - Drivers
  - Constructors
  - Seasons
  - Circuits

---

## 🎛️ Interactivity

The dashboard includes interactive filters for:

- Season
- Driver Name
- Country
- Constructor

This allows users to dynamically explore performance trends across different eras of Formula 1.

---

## 📌 Key Insights

- Identifies the most successful drivers and constructors across seasons.
- Shows how driver performance changes year over year.
- Highlights circuits that have hosted the most races in F1 history.

---

## 🚀 Project Outcome

This project demonstrates skills in:

- Data cleaning and transformation
- Data modeling
- Feature engineering
- Dashboard design
- Interactive data visualization
