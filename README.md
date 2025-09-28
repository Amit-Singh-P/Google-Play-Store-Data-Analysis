# Exploratory Data Analysis (EDA) Project: Google Playstore Dataset

## Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on the Google Playstore dataset. The main objective is to clean, process, and analyze the dataset to extract meaningful insights about app ratings, user engagement, pricing, installs, and release trends over time.

---

## Dependencies

The project uses the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn

Install these dependencies with:
- pip install pandas numpy matplotlib seaborn
---

## Workflow

### 1. Import Libraries
- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import seaborn as sns

### 2. Load and Inspect Data

- Load dataset `Google-Playstore.csv`.
- Examine the data structure, preview rows, check for missing values and duplicates.
- View statistical summaries and correlation of numerical features.

### 3. Data Cleaning

- Drop unnecessary columns such as 'Unnamed: 0'.
- Identify and remove duplicate rows.
- Handle missing values:
  - Fill numerical columns (`Rating`, `Rating Count`, `Minimum Installs`, `Maximum Installs`) missing entries with median.
  - Fill categorical columns with mode.
- Visualize numerical columns with boxplots to identify outliers before imputation.

### 4. Exploratory Analysis

- Identify top apps by rating, average rating, maximum installs, and rating counts.
- Analyze paid apps versus free apps regarding ratings and pricing.
- Aggregate metrics by category including average ratings, total rating counts, and app counts.
- Use groupby and sorting techniques to extract top performers.

### 5. Feature Engineering & Temporal Analysis

- Convert release dates to `datetime`.
- Extract year, month, and day components.
- Analyze app release trends and ratings over years and months using pivot tables.

### 6. Additional Data Handling Example

- Insertion of new rows at specific indices with sorting and resetting index.

---

## How to Use

1. Place `Google-Playstore.csv` in your working directory.
2. Run the provided Python scripts or notebook containing the above steps.
3. Review outputs, visualizations, and summaries to gain insights into Google Playstore apps.

---

## License

This project and dataset are intended for educational and research purposes. Please respect the terms of use related to the dataset.

---

