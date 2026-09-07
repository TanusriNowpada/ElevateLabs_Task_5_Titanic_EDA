# 🚢 Titanic Survival Analysis — Exploratory Data Analysis

**Uncovering the patterns behind who survived the Titanic disaster, using Python-driven data exploration and visualization.**

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-informational)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview

This project explores the Titanic dataset to understand what really influenced passenger survival — combining statistical summaries and visual analysis to move from raw data to clear, evidence-backed insights.

## 📊 Dataset

The dataset contains details of 891 Titanic passengers, including demographic information (age, gender), travel details (class, fare, embarkation point), and survival outcome.

## 🛠 Tools Used

`Python` `Pandas` `Matplotlib` `Seaborn` `Jupyter Notebook`

## 🔍 Approach

The analysis combines statistical exploration — `.info()`, `.describe()`, `.value_counts()` — with visual methods including histograms, boxplots, scatterplots, and a correlation heatmap, to identify patterns and validate them numerically.

## 💡 Key Insights

- **Gender was the strongest predictor of survival** — 74.2% of females survived vs only 18.9% of males
- **Passenger class mattered significantly** — survival rate dropped from 63% (1st class) to 47% (2nd class) to just 24% (3rd class)
- **Wealth correlated with survival** — passengers who paid higher fares were more likely to survive
- Overall survival rate across all passengers: **~38%**
- Data quality gaps were identified — `age` had 177 missing values and `deck` had 688 missing values

## 📈 Visualizations

The notebook includes an age distribution histogram, a fare-by-class boxplot, an age-vs-fare scatterplot colored by survival, and a correlation heatmap across numeric features.

## ✅ Conclusion

Survival on the Titanic wasn't random — it was shaped heavily by gender, class, and fare, reflecting the real-world "women and children first" evacuation priority and the unequal access wealthier passengers had to lifeboats.

---

*Part of a self-driven data analytics learning journey.*
