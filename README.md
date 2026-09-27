# How Many Threes Is Too Many?

An NBA data analysis project exploring whether there is a point where increasing three-point volume stops improving offensive performance.

This project analyzes NBA regular-season data from 2017–2026 and examines the relationship between three-point attempt rate, three-point efficiency, and offensive rating.

## Project Overview

Three-point shooting has become an increasingly important part of NBA offense, but does simply taking more threes lead to a better offense?

I explored this question by analyzing team offensive performance at different levels of three-point volume, building regression models, and using simulation to examine the tradeoff between expected scoring and game-to-game variance.

## Key Findings

- Teams taking fewer than 30% of their field-goal attempts from three had an average offensive rating of approximately **114.9**.
- Teams in the 40–45% range averaged approximately **115.8**.
- Teams taking at least 50% of their shots from three averaged approximately **116.6**.
- Three-point percentage did not decline at the highest-volume levels in this dataset; teams in the 50%+ group shot approximately **37.0% from three**.
- A regression model using three-point attempt rate, three-point percentage, and a quadratic three-point-volume term was used to examine whether the relationship showed evidence of diminishing returns.
- A scoring simulation suggested that increasing three-point volume could produce similar or slightly higher expected scoring while also increasing game-to-game variance.

Overall, the analysis did not reveal a simple universal point where an NBA team begins taking "too many" threes. The results suggest that three-point efficiency and the additional variance created by a high-volume strategy are important parts of the question.

## Methods

The project includes:

- NBA regular-season and playoff data
- Exploratory data analysis
- Three-point volume grouping
- Offensive-rating comparisons
- Regression analysis
- Monte Carlo-style scoring simulation
- Data visualization

## Tools

- Python
- Jupyter Notebook
- pandas
- NumPy
- matplotlib
- statsmodels

## Repository Contents

- `NBA_Three_Point_Analysis.ipynb` — main analysis notebook
- `NBA_Regular_Season_2017_2026.csv` — regular-season dataset used in the analysis
- `NBA_Playoffs_2017_2026.csv` — playoff dataset used in the project

## Video

I also created a video explaining the analysis and results:

**How Many Threes Is Too Many?**

[Watch the full analysis on YouTube](https://www.youtube.com/watch?v=3ldD45evRnY&t=654s)

## Author

**Jed Cain**  
Boston College
