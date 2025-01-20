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
- Data validation and removal of invalid data for relevant columns, negative hours played, age within 1-100, negative player levelnot expected result etc

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

![Image](https://github.com/user-attachments/assets/ee21acbd-2f2a-42df-8474-132e3803b558)

![Image](https://github.com/user-attachments/assets/999ae87d-fa82-4097-99cf-d6a7ce29dff8) 

![Image](https://github.com/user-attachments/assets/e22c25b4-de89-4d25-9cfb-fd10aebeaebf)

![Image](https://github.com/user-attachments/assets/226a09a7-72d1-4a4d-ba9e-f887c9a3c0ea)

![Image](https://github.com/user-attachments/assets/e7a514d9-9a36-4531-88a8-ba8887e638c3)

