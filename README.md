# Neuroflow Assignment


## Running Program

For problem 1 of the assignment I used Jupyter Notebook to write and run python code to make some analysis on the data supplied. To run the code you would need the Jupyter Notebook IDE. You could download the .ipynb file as well as the csv file and the code should run in the IDE. Make sure the .csv file and .ipynb file are in the same folder, so the data can be properly read into the program. 


## Problem 1

### Given the information you have and any light research you’d like to do on the topic, what insights can you draw? What assumptions have you made about the data? 

I have written comments above each graph in the .ipynb file showing my analysis on the data and the graphs

In summary:
The 'mood'and 'sleep' categories have highest frequency in the data. Meaning people are using the apps mostly to track their moods and sleep. Because the frequency of these categories within the data is high, the sample of data is larger meaning you can probably get more accurate insight from this data over the other two categories. So maybe want to focus on analyzing this data over the other category data

The average score between all categories are all similar ranging around just below a 2.5, histograms show similar score ranges for each type. We want to continue tracking this data to see if over time the averages can increase. Looking at the line graph for the average scores over time you can see the slight changes in average scores, however they stay in small range.

Looking at the line graph for the count of each category per month we can also see the changes in the frequency of each category within the data over time. This data can correlate to how many users are using the app and how often the app is being used. We want to get the frequency to increase meaning it is probably being used more often or has more users.


### What are 2-3 additional pieces of information that would be important to collect? 

I believe this subjective metric information will be contained in a database, and that there will most likely be a database for users that contains more in depth information about each user. I think some other factors unique to users such as age, weight, residency, etc. could also affect their health and how they rate or score each category. If we combined the tables based on the user_id we can compare statistics in the user database to the statistics in the subj_measures file and see if any other factors like weight, age, gender is correlated to how users rate each category. For example, I’d like to compare things like age and the scores in each category, or maybe even gender. When doing these comparisons I believe we can find some more valuable insight on the subject. Also relating users past medical history (like if they have other mental, emotional, physical health issues, or take any medication which can influence their health) and scores in each category could also provide some information, and can give a deeper insight into the data, the users, and how the company can help.


## Problem 2

The neuroflow.sql file has the two sql queries "How many users completed an exercise in their first month per monthly cohort" and "which organizations have the most severe patient population" talked about in the second part of the assignment
