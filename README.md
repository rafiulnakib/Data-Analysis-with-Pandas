A Simple project on data manipulation using python


Context
Which Olympic athletes have the most gold medals? Which countries are they from and how has it changed over time?

More than 35,000 medals have been awarded at the Olympics since 1896. The first two Olympiads awarded silver medals and an olive wreath for the winner, and the IOC retrospectively awarded gold, silver, and bronze to athletes based on their rankings. This dataset includes a row for every Olympic athlete that has won a medal since the first games.

Content
The complete dataset consists of 3 different files.

summer, for summer olympics (1896 - 2012)
winter, for winter olympics (1924 - 2014)
country, outlining profiles of each participating countries
Acknowledgements
Data was provided by the IOC Research and Reference Service and published by The Guardian's Datablog.

What is the data saying?
So we can see from above that "country" dataset has 4 columns namely Country, Code, Population and GDP per Capita. The "winter" and "summer" datasets have exact same 9 columns namely Year, City, Sport, Discipline, Athelete, Country, Gender, Event and Medal.

In this project I will try to find answers for the following questions that crossed my mind after briefly inspecting the above data.

If points were given to each types of medals as follows e.g. Gold = 3, Silver = 2, Bronze = 1, which country is the most successful in the history of olympics (summer and winter combined), based on the number of medals won? Also, show a plot of ranking of the countries based on total points accumulated by each participating countries in the history of olympics that have won at least 50 points.

Do the same as question 1 but this time instead of countries, for individual atheletes. This time rank the athletes with at least 12 points.

Compare the number of men's events with the number of women's events in each olympics (both summer and winter) and make plots to visualise the difference.

Is there any relation between the success rate of a participating country with that country's per capita GDP?

Is there any relation between the success rate of a participating country with that country's population?

How many cities have hosted any form of olympics so far? List all the cities and also create a wordcloud with the name of all such cities?
