
# Fitbit Data Analysis — Python Project

This project explores daily activity, fitness, sleep and heart‑rate patterns using **Fitabase Fitbit tracker data**. It demonstrates essential data‑analysis skills including data cleaning, transformation, exploratory analysis, visualisation and interpretation of behavioural trends.  

The goal of this project is to understand how Fitbit users behave across various dimensions including steps, sleep, intensity, heart rate and calories, and to identify meaningful trends that could support health insights, product improvements or personalised feedback mechanisms.

---

## 📁 Project Structure

```text
fitbit-data-analysis-project
│
├── data/
│   └── (Fitabase CSV files)
├── README.md
└── notebooks/  (recommended location for future analysis)
```

---

## 📄 Data Description
The dataset includes multiple Fitabase exports capturing:

Daily activity: steps, distance, activity minutes
Sleep monitoring: sleep duration & sleep quality
Heart‑rate patterns
Calories burned
Hourly and daily intensity metrics

These files collectively describe how participants moved, slept, exercised and expended energy over the tracked period.

## 🔧 Tools & Libraries Used

Python
pandas (data cleaning, wrangling, joins)
NumPy (numerical operations)
matplotlib / seaborn (visualisation)
Jupyter Notebook


## 🧹 Data Cleaning & Preparation
The following steps were applied to prepare the dataset:

Converted date/time columns to proper datetime format
Standardised column names across CSV files
Merged multiple datasets using participant IDs
Checked for null values, duplicates and inconsistencies
Removed or corrected invalid or impossible values (e.g., negative steps or duration)

This ensured a consistent structure for the analysis.

## 📊 Exploratory Analysis & Visualisations

✅ 1. Daily Steps Distribution

<p align="center">
  <img src="https://raw.githubusercontent.com/leightonwilliams46-prog/fitbit-data-analysis-project/main/outputs/charts/Daily_total_steps_over_time.png" width="600">
</p>

Shows how active users are on an average day, highlighting patterns such as:

High‑activity vs low‑activity days
Consistency in step behaviour
Correlation between steps and calories burned

✅ 2. Sleep Duration & Sleep Quality
Visualisations may include:

Total minutes asleep
Time in bed vs time asleep
Relationship between sleep duration and next‑day activity

✅ 3. Heart‑Rate Patterns
Opportunities include:

Daily resting heart rate trends
Peaks during intense activity periods
Hourly heart‑rate breakdowns

✅ 4. Activity Intensity
Analysis may include:

Very Active / Fairly Active / Lightly Active Minutes
Relationship between intensity and steps
Links to calories burned

✅ 5. Calories Burned vs Activity
Charts could show:

Calories vs Steps
Calories vs Total Active Minutes
Day‑of‑week calorie patterns

## 📈 Insights & Interpretation
From Fitbit user behaviour data, we can extract several meaningful patterns:

Users with higher daily step counts consistently record higher calorie expenditure, showing a strong activity–energy relationship.
Sleep duration varies significantly across individuals, with some showing consistent sleep patterns and others demonstrating irregular rest cycles.
Very Active Minutes tend to cluster at specific times of the day, suggesting habitual exercise routines.
Heart‑rate peaks generally align with periods of increased step counts or moderate‑to‑vigorous activity, validating the data quality.
Sedentary minutes form a substantial portion of the day for many participants, offering opportunities for targeted health recommendations.

These observations could be expanded into personalised health insights or behavioural recommendations.

## ▶️ How to Reproduce the Analysis

Clone the repository.
Place all CSV files into the /data directory.
Open the Jupyter Notebook (recommended path /notebooks/fitbit-analysis.ipynb).
Run the cells sequentially to reproduce cleaning, merging, visuals and insights.
Modify the analysis to explore additional behavioural patterns.

## ✅ Recommendations for Further Improvement

Add a complete Jupyter Notebook with code, charts and commentary
Add visuals directly into this README under each insight section
Explore clustering or segmentation (e.g., grouping users by behaviour)
Create a small Power BI dashboard using the cleaned dataset
Add statistical summaries (correlations, distributions, trend lines)

##  ✅ Conclusion
This Fitbit project demonstrates a structured approach to exploring behavioural health data. By cleaning multiple linked datasets, analysing trends across movement, sleep and intensity, and deriving meaningful insights, the project showcases practical skills essential for a Data Analyst role.
Future expansion could include modelling (e.g., predicting calorie burn), advanced segmentation or integration with health‑recommendation systems.
