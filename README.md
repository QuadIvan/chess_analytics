# Chess Peak Analytics: Performance and Demographics of the Elite

## Project Overview
This project explores the career trajectories and demographic patterns of the world's top chess players. By analyzing historical FIDE data, the study aims to identify the prime age for grandmasters and determine if there is a consistent decline in performance over time. Additionally, it examines the global distribution of players by gender and compares consistency across Classical, Rapid, and Blitz formats.

The project demonstrates Python skills for data cleaning, trend smoothing, and interactive visualization, moving beyond basic descriptive statistics into performance analytics.

## Research Questions
1. The Peak Performance Curve: At what age do elite players typically reach their maximum ELO rating? Does the peak happen earlier in the modern engine era?
2. Format Synergy: How strong is the correlation between Classical, Rapid, and Blitz ratings? Are top players universal or format-specific?
3. Global Gender Landscape: Which countries are leading in gender representation within the elite ranks, and where are the largest gaps?
4. The Decline: Using time-series smoothing, can we identify the average age where a player's performance begins a significant downward trend?

## Tech Stack and Skills
* Language: Python 
* Data Wrangling: Pandas, NumPy.
* Analysis Techniques: 
    * Rolling Windows: To smooth rating fluctuations and identify long-term peaks.
    * Correlation Matrices: To analyze the relationship between different chess modalities.
    * Grouping and Aggregation: To compare performance across different generations (cohort analysis).
* Visualization: Matplotlib and Seaborn.
* Forecasting: Basic Linear/Polynomial Regression to model the aging curve.

## Dataset Description
The analysis is conducted using FIDE (International Chess Federation) historical data.
* Target Population: Top 1000 players (active and retired).
* Key Features: Player Name, Country, Gender, Birth Year, Classical ELO, Rapid ELO, Blitz ELO, and Peak Rating Year.

## Project Structure
* data/: Raw and cleaned datasets.
* notebooks/: Jupyter Notebook with the step-by-step analysis (Cleaning, EDA, Visualization).
* src/: Custom Python scripts for data processing.
* visualizations/: Exported charts and insights.

---
**Author:** [Your Name]  
**Level:** Junior Data Analyst  
**Contact:** [Your LinkedIn/Email]
