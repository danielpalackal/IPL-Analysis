# 🏏 IPL Dataset Analysis

A comprehensive data analysis project on the Indian Premier League (IPL) 
using Python, covering everything from exploratory analysis to machine 
learning predictions.

## 📁 Project Structure

**01** 🔍 `eda.ipynb` — Exploratory Data Analysis  
**02** 🏏 `batting.ipynb` — Batting Analysis  
**03** 🎳 `bowling.ipynb` — Bowling Analysis  
**04** 🏆 `teams.ipynb` — Teams & Seasons  
**05** 🤖 `mlpred.ipynb` — ML Predictions  

> Data lives in `dataset/` — notebooks live in `Code Saves/`

## 📊 Notebooks Overview

### 1. Exploratory Data Analysis (eda.ipynb)
- Overview of 17 seasons of IPL data (2007-2024)
- 1,095 matches and 260,920 deliveries analysed
- Toss decision trends, venue analysis and Player of the Match leaders
- Match result type breakdown

### 2. Batting Analysis (batting.ipynb)
- Top 10 all time run scorers in IPL history
- Highest strike rates (min 500 balls faced)
- Most sixes and fours hit
- Runs scored by match phase — Powerplay, Middle and Death overs
- Batting averages (min 50 innings)
- First ball six analysis across all seasons and last 5 years

### 3. Bowling Analysis (bowling.ipynb)
- Top 10 all time wicket takers
- Best economy rates (min 240 balls)
- Most common dismissal types
- Best bowlers in Powerplay and Death overs
- Most bowled dismissals

### 4. Teams & Seasons Analysis (teams.ipynb)
- All time win rates by team
- Season by season wins heatmap
- Average match scores per season
- Toss decision trends over the years
- Batting first vs chasing win rates by team
- Toss win to match win conversion rates

### 5. ML Predictions (mlpred.ipynb)
- Toss win vs match win correlation analysis
- Regression analysis — win rate vs first ball six rate
- Random Forest match winner prediction model (54.1% accuracy)
- Feature importance analysis
- Player clustering by batting style (Anchor, Aggressive, Finisher, Part Timer)
- Head to head win probability for all active team matchups
- Last 5 seasons head to head predictions

## 🔍 Key Findings
- **Chasing teams win 52.8%** of IPL matches — a slight but consistent edge
- **Venue is the most important factor** in predicting a match winner (38% importance)
- **Toss has minimal impact** on match outcomes — only ~50/50
- **First ball sixes and win rate are not correlated** — independent events
- **Gujarat Titans** have the highest all time win rate at 62.2%
- **Wankhede Stadium** is among the most hosted IPL venues

## 🛠️ Libraries Used
- `pandas` — data manipulation
- `numpy` — numerical operations
- `matplotlib` — visualisations
- `seaborn` — statistical charts
- `scikit-learn` — machine learning
- `scipy` — statistical analysis

## 🚀 How to Run
1. Clone the repository
2. Install dependencies: `pip3 install pandas numpy matplotlib seaborn scikit-learn scipy`
3. Open any notebook in VS Code with the Jupyter extension
4. Run all cells top to bottom

## 📅 Dataset
- **Matches:** 1,095 matches across 17 IPL seasons (2007/08 — 2024)
- **Deliveries:** 260,920 individual ball by ball records
