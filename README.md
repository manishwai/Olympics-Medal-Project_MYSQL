# Olympics-Medal-Project_MYSQL
This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016.
Note that the Winter and Summer Games were held in the same year up until 1992.
After that, they staggered them such that Winter Games occur on a four year cycle starting with 1994,
then Summer in 1996, then Winter in 1998, and so on. 

Dataset Schema
**athelete_table2**
ID - Unique number for each athlete
Name - Athlete's name
Sex - M or F
Age - Integer
Height - In centimeters
Weight - In kilograms
Team - Team name
NOC - National Olympic Committee 3-letter code
Games - Year and season
Year - Integer
Season - Summer or Winter
City - Host city
Sport - Sport
Event - Event
Medal - Gold, Silver, Bronze, or NA


**nocregion**
noc: National Olympic Committee code.
region: Region associated with the NOC.

Dataset Link :https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results

This Anlaysis Involve 20 questions/Queries covering basic topics to Intermediate Level Topics such as CTE , Subqueries and Window Function
Questions List:
1)How many olympics games have been held?
2)List down all Olympics games held so far.
3)Mention the total no of nations who participated in each olympics game?
4)Which year saw the highest and lowest no of countries participating in olympics?
5)Which nation has participated in all of the olympic games?
6)Identify the sport which was played in all summer olympics.
7)Which Sports were just played only once in the olympics?
8)Fetch the total no of sports played in each olympic games.
9)Fetch details of the oldest athletes to win a gold medal.
10)Find the Ratio of male and female athletes participated in all olympic games.
11)Fetch the top 5 athletes who have won the most gold medals.
12)Fetch the top 5 athletes who have won the most medals (gold/silver/bronze).
13)Fetch the top 5 most successful countries in olympics. Success is defined by no of medals won.
14)List down total gold, silver and broze medals won by each country.
15)List down total gold, silver and broze medals won by each country corresponding to each olympic games.
16)Identify which country won the most gold, most silver and most bronze medals in each olympic games.
17)Identify which country won the most gold, most silver, most bronze medals and the most medals in each olympic games.
18)Which countries have never won gold medal but have won silver/bronze medals?
19)In which Sport/event, India has won highest medals.
20)Break down all olympic games where india won medal for Hockey and how many medals in each olympic games.

