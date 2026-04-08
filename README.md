# Fitbit Data Analysis Project

This project explores daily activity, sleep behaviour, calorie burn, and movement intensity using Fitbit data from the Fitabase dataset.

The aim of the project is to understand behavioural patterns, visualise trends, and demonstrate data analysis skills using Python and Jupyter Notebook in a clear and accessible way.

---

## Project Overview

The analysis focuses on:
- Daily step counts and movement trends
- Calories burned and their relationship with activity intensity
- Sleep duration and sleep efficiency
- Weekly activity patterns
- Correlations between activity, sleep, and calories
- Behavioural clustering to identify different “types” of days

The project combines multiple datasets together to build a broader picture of daily behaviour rather than analysing each metric in isolation.

---

## Tools & Libraries Used

- Python  
- Jupyter Notebook  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## Repository Structure


fitbit-data-analysis-project/
├── README.md
├── notebooks/
│   └── fitbit_analysis.ipynb
└── outputs/
    └── charts/
        ├── daily_steps_over_time.png
        ├── daily_calories_burned_over_time.png
        ├── steps_vs_calories.png
        ├── activity_intensity_treemap.png
        ├── daily_sleep_minutes.png
        ├── correlation_heatmap.png
        └── activity_clusters.png

---

## Key Visualisations

All charts generated during the analysis are saved in the folder:


outputs/charts/

These include:
- Daily steps over time
- Daily calories burned
- Steps vs calories
- Activity intensity treemap
- Daily sleep duration
- Sleep vs steps
- Sleep vs calories
- Correlation heatmap
- Cluster analysis of activity patterns

These visualisations support the insights discussed in the notebook.

---

## Summary of Findings

- Daily activity levels are generally consistent, with occasional higher‑activity days.
- Calorie burn is strongly influenced by **activity intensity**, particularly very active minutes.
- Sleep duration varies, but does not show a strong relationship with next‑day activity levels.
- Weekly routines influence movement patterns more than sleep quality.
- Correlation analysis confirms strong relationships between steps, intensity, and calories.
- Clustering reveals distinct behavioural “day types”, such as low‑activity days, routine days, and high‑intensity days.

---

## Data Availability

Due to file size constraints, the raw Fitabase CSV files are **not included** in this repository.

To run the analysis locally:
1. Download the Fitabase dataset
2. Place the CSV files into a local `data/` folder
3. Run the notebook from top to bottom

This approach follows standard data analysis best practices for large datasets.

---

## How to Run the Notebook

1. Clone this repository
2. Install the required Python libraries
3. Open the notebook in `notebooks/01_fitabase_analysis.ipynb`
4. Ensure the dataset is available locally
5. Run all cells sequentially

---

## About This Project

This project was created as a data analysis portfolio piece. It demonstrates skills in:
- Data cleaning and preparation
- Exploratory data analysis
- Visualisation
- Insight generation
- Clustering and pattern discovery

The focus is on clear communication of insights alongside technical implementation.
