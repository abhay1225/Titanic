# Titanic
This contains approach to titanic dataset competition hosted on Kaggle

# Story
Sinking of the RMS Titanic is one of the most infamous shipwrecks in history

On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew

Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class

# Problem Defination
Use Machine Learning predict if a passenger survived sinking of the Titanic or not

# Data Description

The data given was split into two sets:

#### Training set – 
It contained the outcome (also known as the “ground truth”) for each passenger. Used to build the model.This has 891 data points.
#### Test set – 
It was used to see how well the model created performs on unseen data. Did not contain the outcome for each passenger. This has 418 data points.

# Approach
1. Exploratory Data Analysis 
2. Missing Value Treatment and Outlier Detection
3. Feature Engineering
4. Feature Dependencies
5. Data Modeling and Validation

# Few key Insights
1. Passengers with PC Ticket type have higher probability to survive, and with A5 or SOTONOQ - lower probability to survive than average

2. Married women could have more chances to survive than single man
This seems logical as Mrs probably had priorities to board surviving boats because they had children with them

3. People in cabin A,B,C which are the top most cabin had the best chances of survival 

4. The Singleton has a low chance of survival as compared to people with family
And, people with small family(less than 4 members) have a better chance of survival as compared to people with large family(5 or more members)




