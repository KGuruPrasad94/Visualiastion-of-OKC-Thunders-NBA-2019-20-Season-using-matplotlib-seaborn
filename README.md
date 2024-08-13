# OKC Thunder 2019/20 NBA Season Visualization

## Project Overview
This project involves the visualization of the Oklahoma City Thunder's 2019/20 NBA season using Python and Tableau. The primary objective is to analyze and gain insights into the team's performance during the regular season and playoffs. The project is divided into two parts: visualizing the regular season performance using Python and visualizing the playoff performance using Tableau.

## Data Sources
- **NBAStats.com**
- **ESPN**
- **Basketball Reference**
- **OKC Thunder's Official Website**

Data was consolidated into an Excel sheet and then imported into a Jupyter Notebook for further analysis and visualization.

## Part 1: Regular Season Visualization (Python)

### Data Processing and Preprocessing
- Cleaned and standardized the dataset by handling null values, correcting erroneous entries, and transforming the format for consistency using Python and pandas.

### Key Visualizations and Insights
1. **Team Performance Overview**: Visualized the number of games played, won, lost, and the win percentage against each opponent.
   - *Observation*: The team had a perfect record against several teams, including the Pelicans, Timberwolves, and Warriors.
  
2. **Points Scored and Conceded**: Bar charts displaying the total points scored and conceded in each game, with average lines for wins and losses.
   - *Observation*: Points conceded in wins were generally lower than in losses, indicating defensive strengths in winning games.

3. **Starting Lineups**: Analysis of different starting lineups and their win percentages.
   - *Observation*: The most frequent lineup had a win percentage of 55.56% in 27 games.

4. **League Performance Comparison**: A colormap showing how OKC Thunder performed in the league compared to other teams.
   - *Observation*: The team ranked well in free throws and 3-point defense but struggled with offensive rebounds.

5. **Player Performance**: Spider plots comparing individual player performances, both offensive and defensive, to their career averages.
   - *Observation*: Players like Shai Gilgeous-Alexander and Danilo Gallinari exceeded their career averages in several metrics.

## Part 2: Playoff Visualization (Tableau)

### Key Visualizations and Insights
1. **Impact Players - Offense**: Bar charts showing key offensive stats like Points Per Game (PPG), Assists Per Game (APG), 3-pointers, and Field Goals (FG).
   - *Observation*: James Harden was the most impactful offensive player in the playoffs for the Rockets.

2. **Impact Players - Defense**: Box plots visualizing defensive stats such as steals (STL), blocks (BLK), and total rebounds (TRB) per game.
   - *Observation*: Robert Covington outperformed everyone in defensive stats during the playoffs.

3. **Team Comparison in Playoffs**: Charts depicting the differences between the Thunder and Rockets during the playoff leg.
   - *Observation*: The Rockets outplayed the Thunder comprehensively, especially in assists, 3-pointers, and steals.

## Conclusion
This project showcases the use of data analytics and visualization tools to gain a deeper understanding of a sports team's performance. The visualizations provide actionable insights into the strengths and weaknesses of the OKC Thunder during the 2019/20 NBA season, both in the regular season and playoffs.

## Technologies Used
- **Python**: Data cleaning, preprocessing, and visualization.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib/Seaborn**: Data visualization.
- **Tableau**: Playoff performance visualization.
- **Jupyter Notebook**: For executing and presenting the Python code.

## Future Enhancements
- **Incorporate advanced analytics**: Integrate more advanced statistical methods to analyze player and team performance.
- **Expand visualizations**: Include interactive dashboards for more dynamic insights.
- **Explore additional datasets**: Add data from other seasons or different teams for a more comprehensive analysis.

---
