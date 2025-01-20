# Data Analyst

## Education
Nottingham Trent University (2018-2021)
BA Economics with International Finance and Banking

## Work Experience
Group Analytics & Insights Business Partner -
Watches of Switzerland Group, November 2024 – Present

Group Analytics & Insights Analyst -
Watches of Switzerland Group, March 2024 – October 2024

Junior Retail Analyst -
Watches of Switzerland Group, November 2022 – March 2024



## Portfolio

Player Behaviour Analysis in Gaming

Source: https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset

Overview:  This dataset was Synthetically produced for Educational purposes.

### Introduction:

This project focuses on analysing a simulated dataset of user data within gaming. From this analysis I will look to extract valuable insight that and use it to recommend actionable decisions.

This dataset includes a range of gameplay metrics and demographic information, as listed below:
- Age
- Gender
- Game Genre Preferences
- Weekly Playtime (derived from average game session length, and sessions played weekly)
- In game purchase activity
- Game Difficulty
- Achievements Unlocked
- Time of day preference
- Geographic location
- Player Level

The data analysis I will use combines both descriptive and predictive modelling techniques such as Linear Regression to examine the relationship between Age and playtime per week. The project also employs the use of key visualisations that portray the trends between player activity, genre popularity and players level progression across a range of demographics.

### Data Cleansing and Preperation

- Data sourced and imported from kaggle.com
- Removed blanks, NaN and Null entries from dataset
- Identified and removal of duplicates
- Converting all columns to suitable data types in order to avoid causing any issues in calculations during analysis
- Standardising and trimming string variables, decimal places
- Data validation and removal of invalid data for relevant columns, negative hours played, age within 1-100, negative player level not expected result etc

### Analysis

_Do players put in more hours weekly as they get older or less?_

After plotting age and hours weekly data onto a scatter graph, I ran a linear regression to find out the relationship between the two variables.
Older players tend to spend slightly more time per week than younger players, however with a slope of 0.15 this is not dramatic. This is supported by a covariance of 14.96, which suggests that there is a significant amount of variability between individuals, so although there is a correlation, there will also be many cases of younger players playing more than older players.
These results could be driven by a number of external factors such as young adults being restricted by parental supervision and a higher focus on schooling, school clubs etc.

To drive action from these results, I would look to suggest if we can establish higher engagement with the younger audience, whether this is through time rewarding features such as season passes, daily challenges, daily log in events. This would also give the older audience oppurtunities to recieve loyalty rewards from their increased playtime.

![Image](https://github.com/user-attachments/assets/b1b115ac-3a1f-43dc-9a4b-4a335a39f5ce)

_Are the majority of the playerbase remaining engaged?_

Below i have plotted a line chart that displays player level on the X axis, and a cumulative percentage of the total playerbase on the Y axis. As we can see there is a fairly linear relationship between the two variables, which shows that there is a steady amount of users progressing at all levels.
With the references lines I've placed, we can see that 50% of the player base are below level 50, and the other 50% above. We can also see that only 10% of the players are surpassing level 84.

This shows a relatively healthy climb in playerbase progression, however these would be key metrics to look at when developing content for the games in question. For example if the late game content is some of the best, then are you happy with only 10% of players experiencing that content, or should it be balanced, or made easier to get to. Similar to this, you could use this visualisation and data to try and obtain areas in which a large portion of the playerbase might switch off or be stuck on. As this is synethetic data, are more realistic look for this line would be more likely to be stepped, with the smaller steps indicating that there are no large sticking points.

The actionable insight I would drive from this is the distribution of the late game content, and how easy it is to get to. I would suggest that the bottom 50% be as smooth of a line as possible, to not deter new players from entering the game, and that they might stay more engaged if they feel quick progression.

![Image](https://github.com/user-attachments/assets/166bd554-f36a-44b1-909d-f0da314604c1)

_What time of day do users play?_

I've used a histogram to illustrate concurrent players during the 24 hour period of the day by hour. Within this data it shows an up and down but steady playercount throughout the day and night with around 1600-1700 players concurrently logged in. However we can also see a steep drop off between 23:00 and 01:00. 
Consistency throughout the day is great to see, and could suggest a healthy switch over between different regions logging in to play, so as one region logs off, another takes its place. The obvious outlier is between 23:00 and 01:00, this suggests a small window of a large amount of the users logging off and not being replaced. 
This would be more challenging to resolve, as player habits and timezones play a far stronger impact on those decisions. You could run events in this window, to try and engage players, however I would actually argue that there is nothing unhealthy about this cool off period as it seems very consistent during the rest of the the 24 hour period. Instead this would be the ideal time to plan maintenance and downtime of the game which would run with the lowest interferance and disruptance to the majority of the users.


![Image](https://github.com/user-attachments/assets/a5fe39f8-6860-4d30-b958-0fa581af048a)


_How much does genre affect the age demographic of the playerbase?_

Using a boxplot, we can see very even and similar distribution across each of the 5 genres listed, with mean average age being around 32-33 years old across the board matching the median. With 50% of players sitting between 23-42 years old. The youngest age is 15 years old, and oldest being 48 these represent the realstic range of age.

Across this data, there is very little difference between genres, with very even distributions, with only slightly smaller interquartile ranges within Simulation games and action which might suggest that there is a particular high proportion of the playerbase within a very particular age range, being 24-42 but is likely smaller than that.
If there were significant differences, for example a mean (black dot) far younger in sports than the other genres, we could infer that there is a strong younger audience making up the playerbase. Actionable insight from this might take one of two directions either you focus further priority on the same age range that is working or trying and drive engagement with some of the more underrepresented demographics. For example, if you have a young player base, you might invest more into driving ads through mobile phone content, such as TikTok, instagram, youtube to get an influx of new players, from a proven demographic. 

![Image](https://github.com/user-attachments/assets/999ae87d-fa82-4097-99cf-d6a7ce29dff8) 

![Image](https://github.com/user-attachments/assets/e22c25b4-de89-4d25-9cfb-fd10aebeaebf)

![Image](https://github.com/user-attachments/assets/226a09a7-72d1-4a4d-ba9e-f887c9a3c0ea)

![Image](https://github.com/user-attachments/assets/e7a514d9-9a36-4531-88a8-ba8887e638c3)

