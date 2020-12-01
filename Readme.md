# R Project on Dublin Marathon Data Set

# Objective 

Objective of this project is to find how participants perform based on their gender, age and also if they have participated individually or are associated with any club.


# Description

The Dublin Marathon data consisted of 22 variables on 16433 observations. 
I decided to remove the variables YouTube, YourRaceVideo and Share as they contained a lot of Na’s and I decided not to use them in our analysis. 
In part 1 I looked at the top 100 places amongst the categories of groups running then looked at the Guntime amongst the different groups. 
I divided up the categories by gender and looked at the proportion of males and females in each category.
In part 2 I looked at the average speed for the first half and last half of the marathon amongst the different running groups. 
Finally, in part 3 I looked at the proportion of each gender in a club or not and then whether the participants were in a club or not by category. 
I ran a linear model to see whether being in a club and your age affected on your finishing time.


After running a model found that the QQ-plot had a skew at the bottom and top, also the interaction term was not significant. 
I then ran a Poisson's glm model and found that age, participation in a club and their interaction were significant in the model.
The QQ-plot of the final model we have chosen is better although we still have a slight skew at the bottom. We also noted that the residuals are evenly spread about zero.

# Conclusion

From the project, we can conclude that twice as many males compete and 95 percent of the top 100 finishers were male. 
The most popular categories are singles and 40’s aged groups for both genders. Single categorized participants seem to have a better gun time. 
It was interesting to see the same trend for average speed amongst the categories for the first half and second half of the marathon.
We suspected that participation with a club would influence your result.
Interestingly there were only 2551(15.5%) participants in a club but the results in the model were still significant.

# Contribution
Alok Kumar Singh, Tara Vivash, Sankdip, Yang
