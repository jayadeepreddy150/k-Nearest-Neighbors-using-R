# k-Nearest-Neighbors-using-R

2.	Explore the overall structure of the dataset using str(). Describe it one paragraph here. Copy and paste the commands and execute results in R console here. (10 points)

3.	Convert the attribute horsepower from character to integer. Copy and paste the commands and execute results in R console here. (5 points)

4.	The horsepower attribute has some missing values. Remove the observations with missing values, i.e., delete the rows with missing values from the data frame. Copy and paste the commands and execute results in R console here. (10 points)

5.	Explore the data in order to investigate the association between mpg and the other features.
Which of the other features seem most likely to be useful in predicting mpg (scatterplots may
be useful tools to answer this question). Describe your findings using a paragraph. Copy and paste the commands and execute results in R console here. (15 points)

6.	Create a new attribute mpg1 that contains 1 if mpg is strictly greater than its median, and 0 if
mpg is equal or less than its median. Copy and paste the commands and execute results in R here. (10 points)

7.	Decide which attributes you are going to use to predict mpg1. Remove all remaining
attributes, including mpg. Copy and paste the commands and execute results in R console here. (10 points)


8.	Set the seed of the random number generator to a fixed integer, say 1, so that you can
reproduce your work:

9.	Normalize the attribute values. Copy and paste the commands and execute results in R console here. (5 points)


10.	Randomize the order of the rows in the dataset. Copy and paste the commands and execute results in R console here. (5 points)


11.	Split the data into a training set and a test set. Use a test set of 100 rows. Copy and paste the commands and execute results in R console here. (5 points)

12.	Perform kNN on the training data, with several values of K, in order to predict mpg1. What
test errors do you obtain? Which value of K seems to perform the best on this data set? Copy and paste the commands and execute results in R console here. (25 points)

