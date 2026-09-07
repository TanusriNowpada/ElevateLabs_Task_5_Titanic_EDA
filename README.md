# 🚢 Titanic Survival Analysis — Exploratory Data Analysis

**Uncovering the patterns behind who survived the Titanic disaster, using Python-driven data exploration and visualization.**

## Overview

This project dives into the Titanic dataset to understand what really influenced survival — using statistical summaries and visualizations to move from raw data to clear, evidence-backed insights.

## Tools Used

`Python` `Pandas` `Matplotlib` `Seaborn` `Jupyter Notebook`

## Key Insights

- **Gender was the strongest predictor of survival** — 74.2% of females survived vs only 18.9% of males
- **Passenger class mattered significantly** — survival rate dropped from 63% (1st class) to 47% (2nd class) to just 24% (3rd class)
- **Wealth correlated with survival** — passengers who paid higher fares were more likely to survive
- Overall survival rate across all passengers: **~38%**
- Data quality gaps were identified — `age` had 177 missing values and `deck` had 688 missing values

## Approach

The analysis combines statistical exploration (`.info()`, `.describe()`, `.value_counts()`) with visual methods — histograms, boxplots, scatterplots, and a correlation heatmap — to identify patterns and validate them numerically.

## Conclusion

Survival on the Titanic wasn't random — it was shaped heavily by gender, class, and fare, reflecting the real-world "women and children first" evacuation priority and the unequal access wealthier passengers had to lifeboats.
