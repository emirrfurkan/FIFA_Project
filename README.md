# EA Sports FC 24 - Player Market Value Analysis ⚽

## Project Overview
This project explores the comprehensive EA Sports FC 24 player dataset to identify the underlying factors driving professional player market valuations (`value_eur`). It covers the end-to-end data science lifecycle, from data cleaning and feature engineering to statistical hypothesis testing.

## Key Highlights
* **Data Cleaning & Feature Engineering:** Handled missing valuation data and engineered a new `potential_growth` metric to capture player development ceilings.
* **Exploratory Data Analysis (EDA):** Visualized demographic distributions, including the core age curve of professional players.
* **Statistical Testing:** Conducted Welch's T-Test, successfully proving a statistically significant market premium for left-footed players due to physical rarity.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Matplotlib, SciPy
* **Environment:** Jupyter Notebook

## How to Run Locally
1. Clone this repository to your local machine.
2. Download the `male_players.csv` dataset from [Kaggle](https://www.kaggle.com/datasets/stefanoleone992/ea-sports-fc-24-complete-player-dataset) and place it in the root directory. *(Note: The dataset is large and ignored via `.gitignore`).*
3. Open and run all cells in `fifa_analysis.ipynb`.