# **Olympic Games Historical Dataset Analysis** ![Icon](https://img.icons8.com/ios-filled/50/000000/olympics.png)

## **Dataset Overview**

This dataset includes historical records from the modern Olympic Games, covering all events from Athens 1896 to Rio 2016. Note that:
- **Winter and Summer Games** were held in the same year until 1992.
- From 1994, the Winter Games were held every four years, alternating with the Summer Games.

### **Dataset Schema**

- **athlete_table2**:
  - **ID**: Unique number for each athlete.
  - **Name**: Athlete's name.
  - **Sex**: Gender (M or F).
  - **Age**: Age of the athlete.
  - **Height**: Height in centimeters.
  - **Weight**: Weight in kilograms.
  - **Team**: Team name.
  - **NOC**: National Olympic Committee 3-letter code.
  - **Games**: Year and season of the Olympic Games.
  - **Year**: Year of the Olympic Games.
  - **Season**: Season of the Games (Summer or Winter).
  - **City**: Host city.
  - **Sport**: Sport played.
  - **Event**: Event in which the athlete competed.
  - **Medal**: Type of medal won (Gold, Silver, Bronze, or NA).

- **nocregion**:
  - **noc**: National Olympic Committee code.
  - **region**: Region associated with the NOC.

[**Dataset Link**](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)

## **Analysis Questions**

This analysis involves 20 questions/queries covering basic to intermediate topics such as Common Table Expressions (CTEs), subqueries, and window functions.

1. **How many Olympic Games have been held?**
2. **List all Olympic Games held so far.**
3. **Mention the total number of nations that participated in each Olympic Games.**
4. **Which year saw the highest and lowest number of countries participating in the Olympics?**
5. **Which nation has participated in all of the Olympic Games?**
6. **Identify the sport that was played in all Summer Olympics.**
7. **Which sports were played only once in the Olympics?**
8. **Fetch the total number of sports played in each Olympic Games.**
9. **Fetch details of the oldest athletes to win a gold medal.**
10. **Find the ratio of male to female athletes participating in all Olympic Games.**
11. **Fetch the top 5 athletes who have won the most gold medals.**
12. **Fetch the top 5 athletes who have won the most medals (gold/silver/bronze).**
13. **Fetch the top 5 most successful countries in the Olympics, defined by the number of medals won.**
14. **List the total gold, silver, and bronze medals won by each country.**
15. **List the total gold, silver, and bronze medals won by each country for each Olympic Games.**
16. **Identify which country won the most gold, most silver, and most bronze medals in each Olympic Games.**
17. **Identify which country won the most gold, most silver, most bronze medals, and the most medals in each Olympic Games.**
18. **Which countries have never won a gold medal but have won silver/bronze medals?**
19. **In which sport/event has India won the highest number of medals?**
20. **Break down all Olympic Games where India won medals for Hockey and specify how many medals were won in each Olympic Games.**


