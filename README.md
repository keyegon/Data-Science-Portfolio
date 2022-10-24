
# Erick Yegon, PhD  Data Science Portfolio

Welcome to my portfolio that shows highlights of some work i have done in my data science journey. As you will see below, in my journey to answer a broad range of data science question my journey has seen me  utilize tools such as:
- R 
- Python
- Postgres SQL


These  projects focuses on my experience around rousing and mining data from wesites, data cleaning and wrangling, Testing statistical analysis, machine learning( supervised and unsupervised  learning) and generating maps

# [Project 1: Which Streaming Service Content had the highest raing content and whether critics and audiences are more aligned toon TV shows in the past: Analysis using SQL](https://app.datacamp.com/workspace/w/6346db3a-a2e9-4b31-9287-45c438911e7a)
* In this project we obtained data from four databses( amazon, hulu, netflix, and disney) and joined. This was followed y cleaning of the data by removing null values in various data tables, in order to determing the most family-friedly streaming services, using pattern matching to find any references to "kids", "family", etc.,
* Determined which streaming services had the highest-rated content using SPLIT_PART() to extract the number from the column and then cast (::) the result as a numeric type
![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/Family%20Oriented.png)

* Finally analyzed the data to  look into whether critics and audiences were more aligned on tv shows in the past. 
![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/average%20over%20time%202.png)

![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/Average%20Difference%20over%20time.png)

This data shows that the [average rotten tomatoes score](https://en.wikipedia.org/wiki/Rotten_Tomatoes) by streaming services was highest for Hulu. TV ratings were similar for disney, netflix and amazon. From this analysis we note that over time the average difference between audiences and critics over time has been increasing and started coming down after the year 2020

# [Project 2: Predicting Customer reviews](https://app.datacamp.com/workspace/w/314d154e-22ea-4efb-b758-efa019946b2d)
## This project was done as part of my Data Science certification at Datacamp.  The project aims to assist  a  manufacturer of motorcycles that successfully launched its first electric moped in India in 2019 and want a classification sustem for customer reviews.

* Problem:  Due to many reviews from people who never owned Moped motorcyles, how do we exclude  reviews from sucj so that we only consider reviews from owners who actually owned moped 

## Solution
Given this is a classification challenge, the solution lies in exploring the data to identify  ownership of moped and  ratings thereof. This is a classification problem as it is a supervised learning approach in which the computer program learns from the data and makes new observations or classifications. I employed a logistic Regression because of its prowess in predicting probabilities between any two classes. Concisely, by looking at historical data, logistic regression can predict whether: A customer is owned or not.  For my comparison model, I chose Decision Tree Classifier as it is easy to interpret and can easily capture Non-linear patterns
![ownership](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/Percent%20Ownership.png)
![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/ratings.png)
![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/confusion%20Matrix.png)

The confusion matrix is useful in comparing the models because it is to be exploited on a data set with known true and false values. In addition it is important to use the recall score as it calculates how many of the actual positives our model capture by labelling it as positive (True Positive). Also, it is the best model metric to use when an inflated cost is associated with a False Negative. The confusion matrix tells us that the total number of accurate predictions for my logistic regression model is more than the number of incorrect predictions. 

For my decision tree model, the total number of accurate predictions is also more than the number of incorrect predictions.The better-performing approach would be the decision tree model, which has more accurate predictions than the logistic regression model. We can clonclude from this prolem that the decision tree model showed better performances compared to the logistic regression model, as shown by the confusion matrix; the recall score also confirms it.

## [Project 3: Reducing Traffic Mortality in the USA](https://app.datacamp.com/workspace/w/def90728-19ec-4a6f-b8e3-a471e2ca07b5)

### In this project we investigate how to derive a strategy to reduce the incidence of road accidents across the USA by looking at the demographics of traﬃc accident victims for each US state. 
![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/car-accident.jpg)

- To get a sense for the distribution of variables within the data and could consist of one histogram per column. It is often a good idea to also explore the pairwise relationship between all columns in the data set by using a using pairwise scatter plots (sometimes referred to as a "scatterplot matrix").
While the rate of fatal road accidents has been decreasing steadily since the 80s, the past ten years have seen a stagnation in this reduction. Coupled with the increase in number of miles driven in the nation, the total number of traffic related-fatalities has now reached a ten year high and is rapidly increasing.
![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/scatter.png)

* We find that there is a lot of variation between states. Now we want to understand if there are patterns in this variation in order to derive suggestions for a policy action plan. In particular, instead of implementing a costly nation-wide plan we want to focus on groups of states with similar profiles. How can we find such groups in a statistically sound way and communicate the result effectively?
![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/scatter%20viz.png)
- We will make use of data wrangling, plotting, dimensionality reduction, and unsupervised clustering.
![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/Kmeans.png)
clusters
![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/clusters.png)

* The data given to us was originally collected by the National Highway Traffic Safety Administration and the National Association of Insurance Commissioners. This particular dataset was compiled and released as a [CSV-file](https://github.com/fivethirtyeight/data/tree/master/bad-drivers) by FiveThirtyEight under the [CC-BY4.0 license](https://github.com/%EF%AC%81vethirtyeight/data).

![](https://github.com/keyegon/Data-Science-Portfolio/blob/main/images/violin%20plot.png)

## [Project 4: Using Natural Language Programming to Predict words](https://ri45rz-erick-yegon.shinyapps.io/Capstone)
This project was prepared as a capstone project for the Coursera/John Hopkins Data Science Specialization.

**Synopsis**
* A predictive text application was developed using a corpora of English text from blog, news, and twitter sources.

* Using a 5-gram dictionary paired with a 'Stupid Backoff' model, the application predicts the next word of sentences from user input with a top prediction rate of 11.51% and top-3 rate of 21.31%.
[The project can be accessed here](https://ri45rz-erick-yegon.shinyapps.io/Capstone)

## 
