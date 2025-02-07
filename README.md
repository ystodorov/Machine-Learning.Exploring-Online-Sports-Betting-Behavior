# Exploring Online Sports Betting Behavior
### by Yuri Todorov

In this project I'll analyze data players's behavious on a sports betting website. I'll also apply several machine learning techniques on it.
The data is downloaded from Kaggle:
https://www.kaggle.com/datasets/bpkapkar/bet-game-data/. There's not a lot of details provided about it however the columns are pretty self-explanatory about what they signify. I'll also use my previous experience with similar datasets working in the iGaming industry to describe each feature.

The project was created as part of an assignment during my education in the AI program of SoftUni.

## Abstract

The project's primary objective is to glean actionable insights into player behavior, laying the groundwork for informed decision-making and strategic interventions.

I'll begin with data cleaning to ensure the integrity of the datasets, followed by a process of feature selection and extraction. Feature engineering will be used to distill key indicators that wil contribute to the creation of meaningful clusters. Finally I'll try to evaluate the effectiveness of the identified clusters using Random forest.

The outcome of the project could be used for segmenting the players into categories that will be visible on their user profiles on the sportsbook website. The category that each player falls in will appear as badge along with their avatar. Examples are: "Bonus opportunist", "Big spender", "Smart bettor", "Heavy Hitter". The idea is the players to have some idea for their gambling style presented in short and funny one or two-word labels. Psychologically this has the potential in a positive way to help the players forward a safer gambling style - like a gentle reminder they've spent too much or encouraging them to use more bonuses and less real money or to know sports better. This would be a gamification that has resposible gambling purpose.

I've used the following two datasets:
 - "depositsdata.csv" - transactional data with deposits made by players on the iGaming website.
 - "betsdata.csv" - encompasses transactional details of player bets

## [I. Initial data manipulations](I.%20Initial%20data%20manipulations.ipynb)
