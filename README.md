# 🏏 IPL 2022 — Capstone Project: Match-level Data Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](./LICENSE)

---

## 🔍 Project Overview
This capstone performs an end-to-end exploratory data analysis (EDA) on **IPL 2022 match-level** dataset to extract insights about match outcomes, player performances, venue trends, toss effects, and top performers.

**Key goals**
- Understand which teams and players performed best.
- Visualize trends (wins, toss decisions, venues).
- Answer targeted questions (highest margin, top scorer, best bowling figures).
- Provide reproducible code and clear findings.

---

## 📁 Dataset
- **File name:** `IPL.csv`
- **Rows / Columns:** `74 rows × 20 columns`
- **Important columns:**

| Column | Type | Description |
|---|---:|---|
| match_id | int | Match identifier |
| date | object | Match date |
| venue | object | Stadium |
| team1, team2 | object | Teams playing |
| stage | object | Tournament stage (Group/Playoffs) |
| toss_winner | object | Toss winner |
| toss_decision | object | Field/ bat |
| first_ings_score, second_ings_score | int | Innings scores |
| match_winner | object | Winner of the match |
| won_by | object | Runs / Wickets |
| margin | int | Margin value |
| player_of_the_match | object | MOM |
| top_scorer | object | Top scorer name |
| highscore | int | Highest individual score |
| best_bowling | object | Bowler with best figures |
| best_bowling_figure | object | e.g. `3--20` |

---

## 🧰 Tech Stack & Dependencies
- Python 3.8+
- Jupyter Notebook
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`

**requirements.txt**
