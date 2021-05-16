# Starbucks-Capstone

As a quest for learning data analytics and data science, I enrolled in the Udacity Data Science Nanodegree. The capstone project requirement is a challenge to analyze three datasets provided by Starbucks.

# Installations
This project requires Python 3.x and the following Python libraries installed:

pandas

numpy

json

seaborn

matplotlib

sklearn

### Data Dictionary

The challenge analyses three separate datasets as contained in the data folder here:
profile.json
It contains the data points like demographics, date of joining, etc., on the various users and members of the rewards program.
portfolio.json
It contains information about the offers sent during 30-day test period. It describes the characteristics of each offer, like the type, its duration, etc.
transcript.json
It contains the event log, that is, whether the offer was received, viewed, or completed. It also contains the customer IDs as well as the offer IDs. It's the most extensive and biggest dataset of all three.

### Code

The code is contained in the notebook Starbucks_Capstone_notebook.ipynb.

### Objective

The objective of this project is to:

I. Perform exploratory analysis of the three datasets.

II. Calculate the success rate of a particular offer.

III. Build a model that can predict the success of the offer.

### Conclusions

1. More men are part of the reward program than women.

2. The median age of a customer is 60 and most of our customers belong to the age range between 40 to 70.

3. The highest number of members earn somewhat around $70k.

4. The income distribution for men is somewhat a normal distribution. More men earn more than $80k than women do.

5. As we can see, this is left-skewed distribution. Most women seem to earn less than 80k.

6. 2017 has the highest number of new members. There is an increasing trend each subsequent year, 2018 being the only exception.

7. More male customers join the program every year.

8. August seems to have the most number of new members, closely followed by October and December.

9. It seems like a large number of offers sent are just viewed by the customers and not completed.

10. Offer id ‘fafdcd668e3743c1bb461111dcafc2a4’ has the highest success rate of 75% while offer id ‘5a8bc65990b245e5a138643cd4eb9837’ has the lowest success rate of just over 6%.

11. We built a Random Forest Classifier model with accuracy above 90% that predicts whether an offer will be successful or not- that is, if a customer will respond to an offer.1


The detailed article on the findings can be found [here](https://renalka.medium.com/starbucks-capstone-project-4b7135577021)
