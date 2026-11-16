# Podium-Power-Analyzing-Olympic-Success

The Olympic Games unite athletes from around the world, fostering a spirit of competition and unity. The International Olympics Committee meticulously records athlete data, event details, and medal distributions to facilitate future Games and improve the overall experience.

As an Analyst working for the International Olympics Committee, we are assigned the crucial task of exploring the extensive dataset covering the Summer and Winter Olympics held between 1896 and 2016. our goal is to provide comprehensive insights into the performance of athletes, medals, and sports during this significant period. Using Tableau, we will analyze the dimensions of athletes, countries, medals, and sports to uncover patterns and trends.

 We have two datasets, each consisting of a table that can be connected via a common column. The first table, named "Olympic Athletes Data," contains detailed information about the athletes who have participated in the Olympic Games. It includes columns such as ID (unique identifier), Name, Sex, Age, Height, Weight, Team, NOC (National Olympic Committee), Games, Year, Season, City, Sport, Event, and Medal. Here is a description of each column:

ID: A unique identifier assigned to each athlete.

Name: The name of the athlete.

Sex: The gender of the athlete (M for male, F for female).

Age: The age of the athlete at the time of participation.

Height: The height of the athlete in centimeters.

Weight: The weight of the athlete in kilograms.

Team: The team representing the athlete.

NOC: The National Olympic Committee code assigned to the athlete's country.

Games: The name of the Olympic Games.

Year: The year in which the athlete participated.

Season: The season of the Olympic Games (Summer or Winter).

City: The host city of the Olympic Games.

Sport: The sport in which the athlete competed.

Event: The specific event within the sport.

Medal: The medal status of the athlete, indicated by Gold, Silver, Bronze, or NA if no medal was won.

 

The second table, named "Olympic Countries Data," contains information about the countries participating in the Olympics. It includes columns such as NOC (National Olympic Committee) and Region. Here is a description of each column:

 

NOC: The National Olympic Committee code assigned to each country.

Region: The region to which the country belongs.

 

By connecting these two tables using the common column "NOC," you can establish a relationship between athlete data and their respective countries, enabling analysis and insights into athletes' performances based on their countries of origin.


Questions:
 

1.            join both the tables after importing them to Tableau.

2.           Create a stacked bar visual to show medal distribution of each country in terms of Bronze, Silver and Gold Medals. Use a filter to show only top 10.

3.           Create a histogram to analyze the age distribution of athletes participating in different sports to identify the age groups that dominate specific events.

4.           Create a histogram to analyze the age distribution of athletes participating in different sports to identify the distribution of Gold, Silver and Bronze medals that dominate specific events.

5.           Create a donut chart to visualize the comprehensive gender distribution of athletes in the Olympics. Provide users with the flexibility to select a specific country of interest and observe the corresponding gender breakdown.

6.           Create a side by side bar chart as per the gender showing distribution of overall Gold, Silver and Bronze Medals.

7.           Create a line chart to showcase the trend of Olympic participation over the years, highlighting the total number of athletes participating in each edition.

8.           Create a line chart to showcase the trend of Olympic participation over the years, highlighting the total number of countries participating in each edition.

9.           Create a Treemap to showcase Top sports as per the total number of medals each sport has received.

10.      Create a Filled Map to showcase total number of medals each country has received.

11.      Create a line chart depicting number of teams participating in Summer and Winter Olympics simultaneously.

12.      Create a KPI for Total Medals, Total Gold Medals, Total Silver Medals and Total Bronze Medals.

13.      Create a KPI for Total Athletes.

14.      Create a KPI for Total Sports

15.      Create an insight other than those mentioned.

16.      Create an interactive Dashboard/Dashboards for all the sheets.

17.      Create a story for all the sheets and dashboards.

