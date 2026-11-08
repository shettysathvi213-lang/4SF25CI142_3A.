# # Zomato Dataset Milestone 1

## Overview

This repository contains the solution for **Milestone 1 – CIE: Data Transformation, Null Value Handling, Insight Generation, and Visualization**.

The project focuses on analysing the Zomato Bangalore Restaurants dataset using Python and various data analysis libraries, including Pandas, NumPy, Matplotlib, and Seaborn.

## Files

- `milestone_1.ipynb` – Jupyter Notebook containing data understanding, preprocessing, missing-value analysis, data transformation, insight generation, and visualizations.
- `zomato.zip` – Compressed Zomato Bangalore Restaurants dataset used for the analysis. It contains the original `zomato.csv` file.
- `README.md` – Project description and instructions.

## Dataset

The dataset contains information about restaurants in Bangalore, including:

- Restaurant names
- Restaurant locations
- Restaurant types and cuisines
- Customer ratings
- Number of customer votes
- Approximate cost for two people
- Online ordering availability
- Table booking availability

## Operations Performed

**Data Understanding:** Loaded the dataset using Pandas and explored its shape, columns, data types, unique values, and statistical summaries.

**Data Cleaning:** Removed duplicate records and unnecessary columns. Converted rating, cost, and votes into appropriate numerical formats.

**Missing Value Handling:** Identified missing values using Pandas and visualized them using a heatmap. Applied mean imputation to numerical columns and mode imputation to categorical columns wherever required.

**Data Transformation:** Created a new feature called `cost_per_person` by dividing the approximate cost for two people by two. Categorized restaurants based on their ratings and applied encoding to categorical variables.

**Insight Generation:** Analysed restaurant ratings, popular locations, restaurant types, cuisines, online ordering trends, table booking facilities, and restaurant costs.

**Data Visualization:** Created visualizations using Matplotlib and Seaborn, including bar charts, line plots, scatter plots, box plots, violin plots, histograms, KDE plots, and correlation heatmaps.

## Key Observations

- Analysed restaurant distribution across different Bangalore locations.
- Identified popular restaurant types and cuisines.
- Examined the distribution of restaurant ratings.
- Compared restaurant costs and calculated cost per person.
- Analysed the relationship between customer votes, ratings, and restaurant costs.
- Explored online ordering and table booking trends.
- Identified and handled missing values in the dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## How to Run

1. Clone or download this repository.
2. Extract `zomato.zip` into the same folder as `milestone_1.ipynb`.
3. Ensure that the extracted CSV file is named `zomato.csv`.
4. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

5. Open the notebook using Jupyter Notebook or JupyterLab.
6. Run all cells sequentially to reproduce the analysis and visualizations.

## Project Details

**Project:** Milestone 1 – Data Transformation, Null Value Handling, Insight Generation, and Visualization

**Dataset:** Zomato Bangalore Restaurants

**Repository:** 4SF25CI142_3A.
