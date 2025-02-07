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

## Key Accomplishments and conclusion
 
 In conclusion, this project represents a comprehensive exploration of sportsbook transactions, leveraging data-driven methodologies to uncover hidden patterns and nuances within player activities. The strategic implications of the findings extend beyond descriptive analytics, offering actionable insights for personalized player engagement and informed risk management. The successful application of unsupervised learning techniques, coupled with model validation, establishes a robust framework for ongoing refinement and optimization of player segmentation strategies. 
 
 I think the project serves its purpose to provide some predictive analytics using key markers of harm to identify trends in risky behavior and determine a players likelihood of becoming different thresholds of at risk.
 
 Further research and exploration of additional features could lead to more nuanced segmentation of the players. I want to apply some dimensionality reduction strategy and re-cluster the players in order to increase the number of groups (potentially by involving the bonus perfromance and the type of sports the player enjoys betting on).
 In conclusion, this project represents a comprehensive exploration of sportsbook transactions, leveraging data-driven methodologies to uncover hidden patterns and nuances within player activities. The strategic implications of the findings extend beyond descriptive analytics, offering actionable insights for personalized player engagement and informed risk management. The successful application of unsupervised learning techniques, coupled with model validation, establishes a robust framework for ongoing refinement and optimization of player segmentation strategies.
 
 Further research and exploration of additional features could lead to more nuanced segmentation of the players. Some additional dimensionality reduction strategy could leverage a more fine-tuned clustering on the players in order to increase the number of groups (potentially by involving the bonus performance and the type of sports the player enjoys betting on). Random forest can also be used to achieve additional predictive analytics using key markers of harm to identify trends in risky behavior and determine a players likelihood of becoming different thresholds of at risk.
 
