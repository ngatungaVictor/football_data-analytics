# Football Match Outcome Analysis

This project explores football match data to understand the relationship between match statistics and match outcomes. Using R, I analyzed Premier League match data, built a simple predictive model, and visualized key insights.

## Dataset
- CSV file: `E0.csv` (Premier League matches)  
- Features included: Home/Away Goals, Shots, Shots on Target, etc.

## Analysis
1. Created `HomeResult` variable: Win, Loss, Draw.  
2. Explored correlation between Shots/Shots on Target and goals scored.  
3. Built a Random Forest model to predict match outcomes.  
4. Visualized Home Shots on Target vs Home Goals:

![Home Shots on Target vs Home Goals](plot.png)

## Key Insights
- Higher Shots on Target strongly correlate with goals scored.  
- Wins are concentrated at higher Shots on Target values, showing **precision beats volume**.  
- Home teams generally take more shots than away teams, but accuracy matters most.  
- Visualizations highlight actionable insights from raw match data.

## Tools
- R: `dplyr`, `ggplot2`, `caret`, `randomForest`  
- Skills demonstrated: data cleaning, analysis, visualization, predictive modeling.

**This mini-project demonstrates ability to collect, analyze, and visualize football data — skills directly relevant to a Sports Data Collector role.**