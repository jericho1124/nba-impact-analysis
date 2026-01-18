# NBA Player Performance Analysis (2024-25 Season)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![NBA-API](https://img.shields.io/badge/Data-NBA_API-orange)](https://github.com/swar/nba_api)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Project Overview
This project is a comprehensive data analysis of the **2024-25 NBA Regular Season**. Using the official NBA Stats API, I performed Exploratory Data Analysis (EDA) to evaluate player efficiency, usage rates, and the impact of the modern 3-point-heavy playing style.

The goal of this portfolio piece is to demonstrate my ability to:
* Extract data from a live **REST API**.
* Clean and preprocess real-world datasets using **Pandas**.
* Calculate advanced efficiency metrics like **True Shooting Percentage (TS%)**.
* Communicate complex data insights through **Seaborn/Matplotlib** visualizations.

---

## Technical Stack
* **Language:** Python
* **Libraries:** * `nba_api`: To fetch live player and team statistics.
    * `pandas`: For data cleaning, merging, and filtering.
    * `matplotlib` & `seaborn`: For creating statistical charts and correlation heatmaps.
    * `numpy`: For handling numerical operations.

---

## Key Analysis Sections

### 1. Data Cleaning & Filtering
To ensure the integrity of the analysis, I filtered the dataset to include only players who:
* Played at least **20 games**.
* Averaged significant minutes per game.
* This prevents "outlier" data from players with extremely small sample sizes (e.g., a player who took only 1 shot all season and made it).

### 2. Efficiency vs. Usage (The "Star" Chart)
One of the core analyses of this project is the **Usage vs. Efficiency** scatter plot. By dividing the plot into four quadrants, I identified:
* **Superstars:** High Usage / High Efficiency.
* **Role Players:** Low Usage / High Efficiency.
* **High-Volume Inefficient:** High Usage / Low Efficiency.

### 3. Age vs. Performance Correlation
Using a **Correlation Heatmap**, I analyzed how age affects scoring, rebounding, and defensive ratings in the modern NBA landscape.

### 4. Shot Distribution Trends
I calculated the **3-Point Attempt Rate** to see how the league's shot selection has evolved, visualizing the distribution of 3PT reliance across different positions.

---

## Featured Visualizations

| Efficiency vs. Usage Scatter Plot | Age/Stats Correlation Heatmap |
| :---: | :---: |
| <img width="400" height="300" alt="Efficiency_vs_usage" src="https://github.com/user-attachments/assets/7b8af746-0bcc-49b4-99bd-2cc30a24a0c6" /> | <img width="400" height="300" alt="heatmap" src="https://github.com/user-attachments/assets/9c94aad8-3218-4e8f-a891-42539959c623" /> |

---

## Key Insights
* **Efficiency Peaks:** In the 2024-25 season, the elite "MVP-level" efficiency threshold sits at a True Shooting percentage of **>62%** with a Usage Rate of **>28%**.
* **The 3PT Revolution:** More than 40% of the league's qualified players now have a 3-point attempt rate higher than 35%, showcasing the "space and pace" era.
* **Veteran Consistency:** While raw scoring (PPG) often peaks in the mid-20s, True Shooting efficiency remains remarkably stable for star players into their early 30s.

---

