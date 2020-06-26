# Project: Business Intelligence with Tableau


## Overview: 
The aim of this project is using Tableau as a tool for visualizing data. For this purpose, a simple dataset (in a .csv format) was choosen from "Google trends" to analyze the number of searches of the terms "Data analysis", and "Data science", and  the topic "Data analysis". 


## Datasets: 
The datasets where obtained from "Google trends":

https://trends.google.com/trends/explore?q=data%20analysis

https://trends.google.com/trends/explore?q=%2Fm%2F07zy4y

https://trends.google.com/trends/explore?q=Data%20science

for the period from 30.06.2019 to 25.06.2020. The datasets used are in a .csv format and are in the "Data" folder of this repository. 

## Tableau: 
As the main aim of the project is to explore the visualization possibilities offered with Tableau, multiple graphs where created and then a group was merged in Dashboards, to be finally compiled in a story tittled: "Trends". 
The story "Trends" has 5 story points, as briefly described below:

Story points: 
1. DA & DS terms timeline: The data for each term was represented by a simple line graph showing the search trend over the given time period.
2. Countries with top interest in both terms: the data was represented by horizontal bar charts and show the countries with highest searches for each of the two terms
3. Interest by Country: the data was represented by a symbol map, showing the interest in each term by the country. * To obtain this map a connection was created joining (outer join) the tables: "DA term geoMap" and "DS term geoMap". 
4. Interest in DA compared to DS as term: the data merged after the outer join was represented in a vertical bar chart. 
5. Interest in DA, DS terms, and DA as topic: the data was obtained after merging the first connection with the table DA topic geoMap. A vertical bar chart was created which allows a view per country.

## Insights:
Tableau proves to be a very valuable tool not only in visualizing data, but also processing. For example, null values were detected by Tableau automatically, and in some cases filtered for enhanced visualization. 

The data shows similar search trends for both terms "Data analysis" and "Data science", and it appeares that countries with highest number of searches are in Asia, India, and Africa.  
