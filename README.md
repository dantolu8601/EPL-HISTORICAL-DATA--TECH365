# EPL-HISTORICAL-DATA--TECH365

EPL HISTORICAL DATA REPORT

PROJECT SCOPE

GOAL

•	Identify top-performing teams at home and away, and those consistently scoring high goals.

•	Examine the impact of yellow/red cards on team win rates and track disciplinary trends over the years.

•	Calculate average goals per match and analyze offensive efficiency through shots on target.

•	Explore referee involvement by the number of matches officiated.

•	Rank teams by total home and away goals and determine the most carded teams annually


PROCESS

1.	Data Cleaning and Preparation
   
Collected data from Kaggle dataset. Used Power Query to remove duplicate entries, ensure correct data types for each column, and also ensured there were no blank cells in the dataset.

2.	Dashboard Design

Imported the cleaned data into Power BI and built an interactive dashboard to analyze Premier League trends.

Focused on key metrics such as team performance, referee statistics, and card distribution.

3.	Implementation
   
Created calculated columns and measures for:

Total matches played, win percentage, and goals scored.

Total yellow and red cards by referees and teams.

Total home and away goals scored by teams.

All calculations were done with the understanding of DAX functions and also the NEW MEASURE TOOL

Designed filters to allow exploration of performance by year, teams, and referees.

4.	Visualizations

Cards:
Displayed total teams, total matches played, total goals scored, and total cards (yellow and red).

Bar Charts:
Top teams by home and away goals scored.

Referee activity, highlighting matches officiated and card distribution.

Line Charts:
Showed trends in team card counts and win rates.

Pie Chart:
Visualized the proportion of yellow cards vs. red cards.

5.	Testing and Validation
Ensured all calculated measures and visualizations dynamically responded to filters and slicers.


INSIGHT QUESTIONS

•	Which team has the highest win home and away over the years?

•	Are there specific teams that consistently score a lot of goal?

•	Which team received the most yellow card and red cards and how does it impact their win rates?

•	What is the frequency of yellow and red cards over the years?

•	Average Number of goals per match?

•	Matches Officiated by Referees?

•	Top 10 Teams by total home goals?

•	Top 10 Teams by total away goals?

•	Most Carded Team by year

•	Average Shot on target per game?


FINDINGS

General Overview:

Total Teams: 46 teams have participated in the Premier League from 2000 to 2024.

Win Rate: The overall win rate is 45.97%, with an average of 2.71 goals scored per match.

Discipline: There have been 30,000 yellow cards and 1,378 red cards distributed across matches.

Referee Statistics:

Mike Dean has officiated the most matches and distributed the highest number of yellow and red cards.

Referees like M. Atkinson and A. Taylor follow closely in total matches and card distributions.

Team Performance:

Top Home Goal Scorers: Arsenal, Man City, and Liverpool lead in total home goals scored.

Top Away Goal Scorers: Newcastle, West Ham, and Everton dominate away goal performance.

Most Carded Teams: Arsenal has the most cards, followed by Everton and Tottenham, indicating discipline challenges.

Card Distribution:

Majority of the cards (yellow and red) were issued for home games, with yellow cards making up 47.79% of total infractions.

RECOMMENDATIONS:

•	Teams like Arsenal and Newcastle should focus on improving discipline to reduce unnecessary cards, which can impact their performance.

•	Clubs should analyze the tendencies of referees like Mike Dean (prone to issuing many cards) to adjust strategies and avoid penalties in critical matches.

•	Focus on promoting home games for top-performing teams like Arsenal and Man City to capitalize on their strong home goal-scoring record.

•	The league can explore stricter measures or educational programs for reducing foul play, especially with such a high number of yellow cards.


