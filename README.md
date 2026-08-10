# IPL 2022 — Exploratory Data Analysis

Exploratory data analysis on IPL 2022 match data — uncovering patterns in team performance, toss strategy, player impact, and venue trends across the season.

## Overview

The Indian Premier League (IPL) is a professional T20 cricket league in India, featuring franchises representing cities. This project explores IPL 2022 match-level data (74 matches, 20 columns) to derive insights on match outcomes, player performances, and team dynamics using pandas, seaborn, and matplotlib.

## Dataset

| Column | Type | Description |
|---|---|---|
| `date`, `venue`, `stage` | string | Match metadata |
| `team1`, `team2` | string | Competing teams |
| `toss_winner`, `toss_decision` | string | Toss outcome and choice (Bat/Field) |
| `first_ings_score`, `second_ings_score` | integer | Innings totals |
| `match_winner`, `won_by`, `margin` | string / integer | Result and winning margin |
| `player_of_the_match` | string | Match MVP |
| `top_scorer`, `highscore` | string / integer | Leading batter and their score |
| `best_bowling`, `best_bowling_figure` | string | Leading bowler and figures |

74 rows, 0 missing values across all columns.

## Key Findings

- **Most successful team:** Gujarat, with **12 wins** — followed by Rajasthan (10), Bangalore and Lucknow (9 each)
- **Toss winner also won the match** in **48.65%** of games — close to a coin flip, so winning the toss wasn't a strong predictor of winning the match this season
- **Top Player of the Match:** Kuldeep Yadav, with **4 awards**
- **Leading run-scorer:** Jos Buttler — **651 runs** (season cumulative), ahead of Quinton de Kock (377)
- **Highest individual score:** Quinton de Kock — **140 runs**
- **Best bowling figures:** four bowlers tied at 5 wickets — Yuzvendra Chahal (5/40), Umran Malik (5/25), Wanindu Hasaranga (5/18), and Jasprit Bumrah with the most economical of the four (5/10)
- **Busiest venue:** Wankhede Stadium, Mumbai — **21 matches** hosted, followed by Dr DY Patil Sports Academy (20)
- **Largest win margin (by runs):** Chennai, winning by **91 runs**

## Visualizations

**Most Match Wins by Team**
![Most Match Wins by Team]<img width="624" height="434" alt="most match win" src="https://github.com/user-attachments/assets/fabea77d-fef8-44bf-bead-ae25095cd3f1" />


**Toss Decision Trends**
![Toss Decision Trends]<img width="563" height="454" alt="toss desicion trend" src="https://github.com/user-attachments/assets/8b8fc53b-0d60-4c6b-bc16-9454dd23506e" />


**Matches Won By (Runs / Wickets)**
![Won By Type]<img width="563" height="454" alt="team winning by" src="https://github.com/user-attachments/assets/f29006f1-7f84-429f-a979-8ad1499c0390" />


**Top 10 Players of the Match**
![Top Players of the Match]<img width="689" height="413" alt="player of the match trend" src="https://github.com/user-attachments/assets/48aba9ac-5ee5-433b-bb0c-9410753f2284" />


**Top Run-Scorers**
![Top Scorers]<img width="552" height="534" alt="top scorer" src="https://github.com/user-attachments/assets/b8181064-b2d6-4ce9-99c2-7a98f2381b6d" />


**Top Bowling Figures**
![Top Bowling Figures]<img width="689" height="413" alt="best bowlers" src="https://github.com/user-attachments/assets/4147478d-63c2-44ff-8995-7945a014144a" />


**Most Matches Played by Venue**
![Most Matches by Venue]<img width="875" height="413" alt="most match played by venue" src="https://github.com/user-attachments/assets/08fb5659-ce45-4d6c-800f-fcf60c6f20b9" />


## Tech Stack

- **Python 3**
- **pandas**, **numpy** — data manipulation
- **seaborn**, **matplotlib** — visualization

## Repository Structure
