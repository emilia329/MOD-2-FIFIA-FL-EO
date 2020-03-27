# MOD-2-FIFIA-FL-EO

Linear Regression Project
Flatiron Module 2 Linear Project Frank Flavell & Emilia Orellana

# Project Overview & Business Case
Scenario: Team Flatiron has struggled to acuire and retain top talent, which has resulted in game losses, a notcable decrease in brand equity, and financial losses in merchandising and ticket sales. They have approached EA Sports to simulate the entire FIFA organization.Their key questions include:

- What are the key characteristics of a top player, which can be identified at the beginning of a career?
- Is there any truth to the old belief that left footed players are more valuable than right footed?
- What is the average value of players based on their age group, especially the 16-19 age range?
- What type of linear regression machine learning model can accurately identify top talent and determine their market value?

# Approach
 Our process had 8 parts.
- Imported dataset from the webiste DataWorld.
- Cleaning the data by removing the null values, and identitfied categorical data and tranformed them.
- Visualizing our insights using Seaborn.
- Checked for correlation 
- Performed Hypothesis tests
- Feature Engineering
- Checked for Normality 
- Regularization 

# Reviewing Dataset
After importing the data, we filtered out the columns we believed would not be necessary and dropped the columns that were repeated. For instance, there was a column for name and full name. We then checked for any missing values and dropped the rows which had missing values for our target variable, value. 


# Analysis using Pandas and Seaborn
We used many DataFrame methods to analyze and clean the data including .describe, .groupby, and .apply. We created new columns for varaibles we created in Feature Engineering. Then we made new dataframes to answer our guiding questions and then visualize our analysis using Seaborn graphs and charts.

# Findings 
We determined there is so significance between left and right footed players and their value. 
graph.

![Bar Graph](https://github.com/emilia329/MOD-2-FIFIA-FL-EO/blob/master/Graphs/graph3.png)

In addition, we also looked into a players ball control and dribbling based on their preferred foot and both showed to be linear. 

![Scatter Plot](https://github.com/emilia329/MOD-2-FIFIA-FL-EO/blob/master/Graphs/graph2.png)

We identified a no signifance between age ranges of 16-19 and 30-39. 

![Bar Graph Ages](https://github.com/emilia329/MOD-2-FIFIA-FL-EO/blob/master/Graphs/graph.png)

# Recommendations
    We recommend..
- There is no need to specifically looking for a left foot player as many believe they are the most expensive.
- Investing in the youngest age range 16-19 may benefit because the next age range 20-29 is the age players are at their peak therefore more expensive. The youngest age group and the group of already experienced players 30-39 show no significant difference in their value. 
- For the future, we can explore advantages and disadvantages between the age groups, specifically social media and early injuries.
- In addition, for the future we can explore if diversity has a positive influence on club recogniton, and fan base. 