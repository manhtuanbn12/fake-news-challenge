# fake-news-challenge 
# This is my first project to learn Data Science 
I use the data and materials from this competition site: http://www.fakenewschallenge.org/ 


The purpose of the project is to try to train and predict the category of a piece of new based on the compatibility between its headline  and its body. This is called as Stance Detection. 


# Problem statement:
*  Input: A headline and a body text 
*  Output: label/decision of whether the body agrees/ disargees/ discusses/ unrelated with the topic. 
# Data:
* File train_stances.csv has the information of stances for train data
* File train_bodies.csv maps bodyID with body content
* File test_stances.csv and test_bodies.csv has the same information for the test data
I do some data cleaning, feature extraction using tf-idf and experiment with some common classification algorithms.

