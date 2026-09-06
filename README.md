# Formula 1 Data Analysis Dashboard

## Project Overview

An end-to-end data analytics project analyzing historical Formula 1 race data using Excel, Power Query, and Tableau. The project explores driver, constructor, and circuit performance across multiple decades of Formula 1 racing.

## Objectives

- Analyze driver performance across seasons.
- Compare constructor performance based on wins and points.
- Identify circuits with the highest race frequency.
- Analyze year-over-year changes in driver performance.
- Build an interactive dashboard for exploring Formula 1 history.

## Dataset

- **Source:** Kaggle, Formula 1 World Championship Dataset
- **Coverage:** 1950-2020
- **Master Dataset:** 26,759 rows

The dataset contains historical information on:

- Drivers
- Constructors
- Circuits
- Race Results
- Lap Times
- Seasons

Multiple CSV files were combined and transformed into a structured dataset for analysis.

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data storage and analysis |
| Power Query | Data cleaning and transformation |
| Tableau | Interactive dashboard and visualization |
| Data Modeling | Combining relational datasets |
| Feature Engineering | Creating analytical metrics |

## Data Cleaning & Transformation

- Consolidated multiple CSV files into a single Excel workbook.
- Corrected data types using Power Query.
- Handled missing values.
- Standardized column formats.
- Merged relational tables using ID keys.
- Created a 26,759-row master dataset.
- Engineered additional analytical features:
  - Win indicators
  - Podium indicators
  - DNF indicators
  - Positions gained or lost
  - Driver age at race
  - Lap time converted to seconds

## Data Analysis

The analysis focuses on driver, constructor, circuit, and seasonal performance.

Key analyses included:

- Driver wins, podiums, and points.
- Constructor wins and total points.
- Circuit race frequency.
- Year-over-year driver point changes.
- Percentage change in driver performance.
- Driver and constructor comparisons across seasons.

## Dashboard

The dataset was connected to Tableau to create an interactive Formula 1 dashboard containing:

- **Top N Drivers Chart:** Compares driver wins, podiums, and points using a dynamic parameter.
- **Constructor Performance Chart:** Dual-axis visualization comparing wins and total points.
- **Circuit Map:** Geographic visualization showing circuits and race frequency.
- **Year-over-Year Driver Performance:** Displays point changes and percentage differences.
- **KPI Cards:** Total Races, Total Laps, Drivers, Constructors, Seasons, and Circuits.

## Key Insights

- Identifies the most successful drivers across Formula 1 seasons.
- Highlights constructors with the strongest overall performance based on wins and points.
- Shows how individual driver performance changes across seasons.
- Identifies circuits that have hosted the highest number of races.
- Enables comparison of performance across different eras of Formula 1.

## Project Structure

```text
Formula-1-Data-Analysis-Dashboard/
│
├── Data/
│   ├── Raw CSV files
│   └── Master dataset
│
├── Excel/
│   └── Cleaned and transformed dataset
│
├── Power Query/
│   └── Data transformation workflow
│
├── Tableau/
│   └── Formula 1 Dashboard
│
├── Images/
│   └── Dashboard screenshots
│
└── README.md
```

## Conclusion

This project demonstrates an end-to-end workflow for transforming historical Formula 1 data into an interactive analytics dashboard. By combining Power Query for data preparation with Tableau for visualization, the project provides insights into driver, constructor, circuit, and seasonal performance across 70 years of Formula 1 racing.
