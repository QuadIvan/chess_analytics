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
1. **Generational Performance:** How is the ELO rating distributed across different age groups in 2025? Are younger generations showing higher average ratings than their veteran counterparts?
2. **Format Synergy:** How strong is the correlation between Standard, Rapid, and Blitz ratings? Do elite players maintain a "universal" level, or are there rhythm-specific specialists?
3. **Geopolitics of Chess:** Which federations currently dominate the Grandmaster landscape in terms of both quantity and average performance?
4. **Gender Representation:** What is the current state of gender diversity within the Grandmaster title, and how does it vary by region?

## Tech Stack and Skills
* **Language:** Python
* **Data Wrangling:** Pandas, NumPy (Data cleaning, type optimization, and feature engineering).
* **Analysis Techniques:**
    * **Structural Auditing:** Ensuring data integrity through density and schema verification.
    * **Correlation Analysis:** Utilizing heatmaps to measure synergy between time controls.
    * **Categorical Optimization:** Reducing memory footprint and improving processing speed through appropriate data types.
* **Visualization:** Matplotlib and Seaborn for demographic and performance distribution.

## Dataset Description
The analysis focuses on the **Grandmaster (GM)** subset of the FIDE list:
* **Target Population:** Active Grandmasters.
* **Key Features:** Player Name, country, Gender (sex), Birth Year (birthday), Age, and Ratings for Standard, Rapid, and Blitz formats.

## Project Structure
* `data/`: Raw and cleaned datasets.
* `notebooks/`: Jupyter Notebook containing the structural audit, data cleaning, and Exploratory Data Analysis (EDA).
* `scripts/`: Custom Python logic for data cleaning and type casting.

---
