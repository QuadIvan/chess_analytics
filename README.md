# Chess Landscape 2025: Performance & Demographics of the Modern Elite

## Project Overview
This project provides a data-driven snapshot of the global chess elite as of late 2025. Using official data from the **International Chess Federation (FIDE)**, the study analyzes the current distribution of Grandmasters, exploring the relationship between different game formats (Standard, Rapid, and Blitz) and examining how performance scales across different age groups and federations.

The project demonstrates advanced Python skills for **structural data auditing**, **memory optimization**, and **multi-format correlation analysis**, providing insights into the modern professional chess ecosystem.

## Data Source
The data was sourced from the official FIDE database.
* **Source Link:** [FIDE Ratings Archive](https://ratings.fide.com/download_lists.phtml)
* **Data Snapshot:** December 2025
* **Dataset Scope:** Grandmasters (GMs) and Women Grand Masters (WGMs), including Standard, Rapid, and Blitz ratings.

## Research Questions
1. **Gender Dynamics & Representation:** What is the current state of gender diversity within the elite Grandmaster landscape, and how do participation density and regional models influence performance outcomes?
2. **Geopolitics of Excellence:** Which national federations dominate the professional circuit, and how do "Volume-based" models compare to "Efficiency-based" institutional models?
3. **Format Synergy & Universal Mastery:** How strong is the correlation between time controls? Does the elite ecosystem favor rhythm-specific specialists, or is there a "Systemic Gravity" toward universal proficiency?
4. **Performance Lifecycle & Generational Decay:** How does age influence competitive strength? Is there a measurable "inflection point" where strategic experience begins to compensate for the decline in computational speed?

## Executive Summary: The State of the FIDE Elite (December 2025)

* **Demographic Reality:** The elite ecosystem remains a mature and male-dominated environment. With a median age of 40 and 86.1% male participation, the "participation gap" continues to be the primary structural feature of the circuit. While the male cohort holds the highest absolute ratings, the "Female GM" category shows the highest technical efficiency relative to their small population size.

* **The Myth of the Specialist:** Elite chess is fundamentally "universal." High correlations between all time formats prove that mastery in one area almost always translates to the others. High-level consistency is a hallmark of professional maturity, while relative specialization is more common in the early stages of a career.

* **The 40-Year Threshold:** Age is a decisive factor in performance. While classical chess strength begins to decline after age 40 due to the high physical demand, faster formats (Rapid and Blitz) remain stable for much longer. This allows veteran players to maintain their elite status through intuition and experience even when their calculation speed slows down.

* **Geopolitics of Excellence:** Global dominance is split between nations with high volume (USA, Germany) and those with high efficiency (China, Uzbekistan). China remains the gold standard for institutional success, particularly in developing the world’s most elite female players.

* **The Universalist Apex:** Absolute mastery across all formats remains the rarest feat in the game. Only three players —Magnus Carlsen, Hikaru Nakamura, and Alireza Firouzja— currently maintain Top 10 positions in Standard, Rapid, and Blitz simultaneously. Magnus Carlsen represents the statistical ceiling of the entire dataset, holding the #1 spot in every category.

## Tech Stack and Skills
* **Language:** Python
* **Data Wrangling:** Pandas, NumPy (Advanced data cleaning, IQR-based outlier detection, and feature engineering).
* **Statistical Analysis:**
    * **Correlation Modeling:** Utilizing Pearson coefficients and heatmaps to quantify skill transferability across formats.
    * **Demographic Segmentation:** Generational cohort analysis and participation density studies.
    * **Performance Metrics:** Comparative analysis using Robust Statistics (Medians vs. Means) to mitigate sample size bias.
* **Visualization:** Matplotlib and Seaborn for multi-dimensional performance distribution and geopolitical mapping.

## Dataset Description
The analysis focuses on the high-performance subset of the December 2025 FIDE list:
* **Target Population:** Active Grandmasters (GM) and Woman Grandmasters (WGM).
* **Key Features:** National Federation (country), Gender (sex), Birth Year, Calculated Age, and synchronized Ratings for Standard, Rapid, and Blitz formats.
* **Data Integrity:** Filtered through Interquartile Range (IQR) methods to ensure a modern professional baseline.

## Project Structure
* `data/`: Contains both the raw FIDE datasets and the processed/cleaned versions.
* `notebooks/`: Comprehensive Jupyter Notebooks detailing the structural audit, IQR-based data cleaning, and Exploratory Data Analysis (EDA).
* `figures/`: Exported visualizations, including performance heatmaps, demographic distributions, and geopolitical dashboards.
* `README.md`: Project documentation and executive summary of insights.

---
