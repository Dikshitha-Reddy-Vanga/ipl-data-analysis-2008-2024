# IPL Data Analysis (2008–2024)

An end-to-end data analysis project exploring 17 years of Indian Premier League (IPL) data to uncover patterns, evaluate team and player performance, and derive meaningful insights.

---

## Project Overview

This project analyzes IPL match data from 2008 to 2024 using Python. It involves data cleaning, preprocessing, exploratory data analysis (EDA), and visualization to understand trends in match outcomes, team dominance, and player performance.

---

## Dataset Information

* Source: Kaggle (IPL Matches Dataset)
* File Used: ipl_matches_2008_2024.csv
* Records: 1095 rows
* Features: 21 columns

### Key Columns

* season, date
* team1, team2, winner
* toss_winner, toss_decision
* player_of_match
* result, result_margin
* target_runs, target_overs
* match_type, super_over, method
* umpire1, umpire2

---

## Problem Statement

To analyze IPL match data from 2008 to 2024 in order to identify hidden patterns, evaluate team and player performances, and generate insights that can help understand match outcomes and tournament trends.

---

## Tech Stack

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

```id="n8k2sa"
IPL_Analysis.ipynb
ipl_matches_2008_2024.csv
README.md
```

---

## Data Cleaning and Preprocessing

* Handled missing values in key columns such as city, winner, and player_of_match
* Replaced null values with meaningful defaults
* Standardized team names for consistency across seasons
* Mapped old franchise names to current ones
* Encoded categorical variables for analysis
* Created derived columns like season_short for better visualization

---

## Exploratory Data Analysis

### Summary Statistics

* Average result margin is around 13.9 runs
* High variation in match scores
* Certain umpires appear frequently

### Correlation Analysis

* Moderate positive correlation between target_runs and result_margin
* Higher targets often lead to larger winning margins

---

## Visualizations and Insights

* Histogram: Most matches are won by small margins
* Scatter Plot: High targets do not always ensure large margins
* Boxplot: Variability in match outcomes across seasons
* Bar Chart: Mumbai Indians and Chennai Super Kings dominate total wins
* Pie Chart: Teams prefer fielding first after winning toss
* Count Plot: Number of matches increased over seasons
* Line Chart: Average winning margins fluctuate over time
* Player Analysis: Top players consistently influence outcomes
* Heatmap: Toss advantage is present but not decisive
* Championship Analysis: CSK and MI lead in total titles

---

## Key Insights

* IPL is highly competitive with many close matches
* Team consistency plays a major role in long-term success
* Toss advantage exists but does not guarantee victory
* Player performance significantly impacts match outcomes
* Match trends and strategies have evolved over seasons

---

## How to Run

1. Clone or download the repository
2. Open the notebook file `IPL_Analysis.ipynb`
3. Ensure required libraries are installed:

```id="k3l9qp"
pip install pandas matplotlib seaborn
```

4. Run all cells in Jupyter Notebook

---

## Future Improvements

* Build predictive models for match outcomes
* Create interactive dashboards using Power BI or Tableau
* Perform player-level deep analysis
* Integrate real-time IPL data APIs
* Add machine learning models for score prediction

---

## Author

Dikshitha Reddy Vanga

---

## License

This project is open-source and available under the MIT License.
