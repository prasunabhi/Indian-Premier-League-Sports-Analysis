# Sport Analysis: Cricket - Scripting for Data Analysis

## Overview
This project involves a comprehensive data analysis of the Indian Premier League (IPL) dataset from 2008 to 2017, covering match details, player statistics, and team insights. The primary objective is to explore team performance trends, the impact of winning the toss, match location influence, player performance, and match result determinants to provide actionable insights for cricket management and operations stakeholders.

## Key Features
* **Data Integration:** Merging match and player-by-match datasets to create a comprehensive database for analysis.
* **Data Cleaning:** Addressing missing values and ensuring data quality for accurate analysis.
* **Analytical Insights:** Investigating team performance trends, toss impact, venue influence, player performance, and win margins.
* **Visualization:** Utilizing Python for visualizing results to aid decision-making.

## Methodology
1. **Data Cleaning and Preparation:**
    * Handled null values in critical columns such as Bowling Skill, Match Winner, Win Type, and Win Margin based on contextual research.
    * Merged datasets: Player by match (13,993 data points, 22 columns) and Match (637 data points, 17 columns).
   
2. **Data Analysis:**
    * **Team Performance:** Analyzed performances of teams with at least 8 seasons, focusing on win percentages and trends.
    * **Toss Impact:** Calculated the correlation between winning the toss and match outcomes.
    * **Venue Analysis:** Assessed how different venues affect match results based on batting or fielding first.
    * **Player Performance:** Evaluated player contributions, man of the match awards, and captain effectiveness.
    * **Win Margin:** Examined whether runs or wickets are more critical for winning matches.
   
3. **Visualization Tools:**
    * Python libraries used: pandas, numpy, matplotlib, ipywidgets, seaborn.
    * Created interactive visualizations to effectively communicate insights.

## Key Findings
* **Team Performance:**
    * Chennai Super Kings, Mumbai Indians, and Sunrisers Hyderabad have the highest win percentages.
    * Sunrisers Hyderabad and Chennai Super Kings show consistent performance trends.
* **Toss Impact:**
    * Winning the toss does not guarantee a match win (correlation: 0.4619).
    * Team performance and strategies play significant roles.
* **Venue Analysis:**
    * M Chinnaswamy Stadium favors teams that field first.
    * MA Chidambaram Stadium is advantageous for teams that bat first.
* **Player Performance:**
    * Man of the match awards typically go to players from winning teams.
    * Effective captains positively influence team performance.
* **Win Margin:**
    * Large run margins indicate dominance, while narrow wicket margins show resilience.

## Conclusion
The analysis provides detailed insights into IPL team and player performance dynamics, offering strategic advantages for cricket management. By understanding the influence of various factors on match outcomes, teams can make informed decisions to enhance their performance and increase their chances of success in future seasons.

## References
* **Main dataset:** [IPL Data till 2017](https://data.world/raghu543/ipl-data-till-2017)
* **Match dataset:** [Match.csv](https://data.world/raghu543/ipl-data-till-2017/workspace/file?filename=Match.csv)
* **Player by match dataset:** [Player_match.csv](https://data.world/raghu543/ipl-data-till-2017/workspace/file?filename=Player_match.csv)
* **Research on null values:** ESPN Cricinfo, Cricketwa, Business Standard
