
# Fitbit Data Analysis — Python Project

## 📌 Executive Summary
This project analyses daily activity, sleep behaviour, heart‑rate patterns and calorie expenditure using Fitabase Fitbit tracker data. The aim is to uncover behavioural trends across steps, intensity, sleep and calorie burn that can support meaningful health insights, user‑behaviour understanding, or future personalised recommendations.

---

## 📁 Quick Access
📓 **Full Jupyter Notebook:** [01_fitabase_analysis.ipynb](notebooks/01_fitabase_analysis.ipynb)  
📁 **All Charts:** [outputs/charts](outputs/charts)

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
Hourly & daily intensity metrics

Together, these files describe how participants moved, slept, exercised and expended energy over the tracked period.

## 🔧 Tools & Libraries Used

Python
pandas — data cleaning, wrangling and joins
NumPy — numerical operations
matplotlib & seaborn — visualisation
Jupyter Notebook — exploratory analysis

## 🧹 Data Cleaning & Preparation
The following steps were applied to prepare the dataset:

Converted date/time columns to proper datetime format
Standardised column names across CSV files
Merged datasets using consistent participant IDs
Checked for null values, duplicates and inconsistencies
Removed or corrected invalid values (e.g., negative steps or duration)

This ensured a consistent structure for reliable analysis.

## 📊 Exploratory Analysis & Visualisations

✅ 1. Daily Steps Distribution

<p align="center">
  <img src="https://raw.githubusercontent.com/leightonwilliams46-prog/fitbit-data-analysis-project/main/outputs/charts/Daily_total_steps_over_time.png" width="600">
</p>

Daily step patterns show clear fluctuations across the time period, with noticeable high‑activity and low‑activity days. This visual also highlights consistency differences between users and potential links between activity volume and overall calorie expenditure.

✅ 2. Sleep Duration & Sleep Quality
Visualisations may include:

Total minutes asleep

<p align="center">
  <img src="https://raw.githubusercontent.com/leightonwilliams46-prog/fitbit-data-analysis-project/main/outputs/charts/Daily_total_minutes_asleep_over_time.png" width="700">
</p>

Sleep duration varies considerably across days, reflecting both consistent sleepers and those with irregular sleep schedules. Fluctuations may influence next‑day behaviour and activity intensity.

Sleep efficiency over time

<p align="center">
  <img src="https://raw.githubusercontent.com/leightonwilliams46-prog/fitbit-data-analysis-project/main/outputs/charts/Sleep_efficiency_over_time.png" width="700">
</p>

Sleep efficiency remains relatively stable with occasional dips, suggesting that users generally maintain consistent sleep quality despite variations in total sleep duration.

✅ 3. Activity Intensity
Analysis may include:

Very Active / Fairly Active / Lightly Active Minutes

<p align="center">
  <img src="https://raw.githubusercontent.com/leightonwilliams46-prog/fitbit-data-analysis-project/main/outputs/charts/Activity_intesity_distribution.png" width="700">
</p>

The visual highlights that sedentary minutes account for the largest proportion of daily behaviour, while moderate‑to‑vigorous intensity minutes occur less frequently. This distribution demonstrates opportunities for targeted activity recommendations.

✅ 4. Calories Burned vs Activity
Charts could show:

Calories burned over time

<p align="center">
  <img src="https://raw.githubusercontent.com/leightonwilliams46-prog/fitbit-data-analysis-project/main/outputs/charts/Daily_calories_burned_over_time.png" width="700">
</p>

Calorie expenditure trends follow a similar pattern to daily steps, showing consistent peaks and troughs. This illustrates the strong link between movement volume and energy output.

Calories vs Total Active Minutes

<p align="center">
  <img src="https://raw.githubusercontent.com/leightonwilliams46-prog/fitbit-data-analysis-project/main/outputs/charts/Relationship_between_total_steps_and_calories_burned.png" width="700">
</p>

A clear positive correlation appears between total steps and calories burned, reinforcing the expected relationship between physical activity and energy expenditure.

## 📈 Insights & Interpretation
From the dataset, several behavioural observations emerge:

Higher daily steps consistently correlate with higher calorie burn, highlighting a strong activity–energy link.
Sleep duration varies widely between individuals, with some maintaining stable patterns and others showing irregular cycles.
Very Active Minutes tend to cluster at particular times of day, suggesting habitual exercise windows.
Heart‑rate peaks generally align with moderate‑to‑vigorous activity periods.
Sedentary minutes occupy a large proportion of the day, indicating opportunities for lifestyle interventions or step‑break prompts.

These findings can inform personalised health recommendations or product‑level insights.

## ▶️ How to Reproduce the Analysis

📘 **Full Jupyter Notebook:** [01_fitabase_analysis.ipynb](notebooks/01_fitabase_analysis.ipynb)

Steps:

Clone the repository
Place all CSV files into the /data directory
Open the Jupyter Notebook
Run all cells sequentially to reproduce cleaning, merging, visualisation and insights
Modify or extend the analysis as required

## ✅ Recommendations for Further Improvement

Expand the Jupyter Notebook with additional commentary
Add summary tables for correlations, distributions and outliers
Explore user clustering (e.g., active vs sedentary groups)
Build a small Power BI dashboard to complement the analysis
Explore predictive modelling (e.g., estimating calorie burn or sleep efficiency)

##  ✅ Conclusion
This project demonstrates a structured approach to analysing behavioural health data. By cleaning multiple linked datasets and exploring trends across movement, sleep and intensity, it highlights practical analytical skills relevant to Data Analyst roles. Future extensions may include predictive modelling, deeper segmentation or integration with personalised recommendation systems.
