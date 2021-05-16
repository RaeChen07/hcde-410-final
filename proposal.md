## Motivation and problem statement:

For the final project, I plan to do an analysis of the Seattle crime data. I am curious that does the main event like BLM and COVID around recent years change the behavior in crime. I am choosing this topic because I am really interested in this topic, and for me, Seattle is still a new city to live in. I want to know how the crime looks like in this area. I hope to learn around the time of the event that affects the police force, does crime rate also get affected. And is there a significant change in behavior of crime during the pandemic. And also I wonder does weekday and weekend make a difference.

## Data selected for analysis:

I am planning to use the Seattle government database at https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5. This database has a Public Domain License. It contains the time, type of crime, and other data in it from 2008 to now. Government data is reliable and the most important thing to my goal is time and crime. Which this database have.

## Unknowns and dependencies:

I might have a really hard time writing code to do what I want. Since I haven't written any complicated code in a long time. I think I can pull it off in time. Just a warning the presentation is going to be a mess. I am not good at speaking English and in front of other people :(.

## Research questions (or hypotheses): These describe what you hope to discover or determine in the course of your research project.

1. Q: What is the impact of days in a week on the number of Burglaries?
   H: Burglary happens more on weekdays than on weekends (explanation: people are more likely to stay home on the weekend which makes burglary hard.).
2. Q: How has COVID impact on numbers of Burglary?
   H: Burglary decrease during COVID (explanation: people are more likely to be at home.).
3. Q: How has BLM incidence impact on numbers of Burglary?
   H: Burglary increases a little bit during BLM incidence (explanation: heard a lot of smashing shops on the news.).
4. Q: How does the crime rate around UW compare to the rest of the Seattle Area?
   H: The area around UW has less crime (I hope).

## Background and/or Related Work: No matter what you choose to investigate, it’s almost certain that someone has investigated it (or a related phenomenon) before. Scientists always review previous work when beginning a new research study.

https://econofact.org/crime-in-the-time-of-covid.
The above article did research on all crime in the US and analyzed the impact of COVID and a little bit BLM. For burglary, this article finds that residential burglary decreases and non-residential burglary increases. But it does not have any information on the overall COVID impact on burglary (and also not a local analysis). I want to find out if Seattle follows the trend of the US or if it has a surprising outcome.
https://en.wikipedia.org/wiki/Impact_of_the_COVID-19_pandemic_on_crime
The Wikipedia page of Impact of the COVID-19 pandemic on crime stated that some type of crime dropped significantly while other increase. Burglary does not seem to be in the increasing crime category. The Wikipedia page gives five types of main increasing crime including Counterfeiting and fraud, Cybercrime, Domestic violence, Hate crimes, and Terrorist attacks. In the hate crime section it stated "increase of hate crime incidents against Asian Americans". This makes me wonder if Seattle has the same problem, but unfortunately the database I plan to use does not have a hate crime category.

## Methodology: Describe how you plan to investigate this phenomenon.

1. Isolated the burglary data and divide them into two group, weekdays and weekend. Get the number of data in each group, devide the weekdays group by 5 and weekend by 2 to get the mean number per day. Plot them in a bar graph and calculate the difference persentage.
2. Isolated the burglary data from 2019 to 2020. Graph line graph for the year 2019 and another for 2020. Compare the two graphs to see if there is a big difference on the number of burglary.
3. Isolated the burglary data in 2020 from May to July. See if there is an unusual trend around this time.
