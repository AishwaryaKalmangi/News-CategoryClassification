1.	News-CategoryClassification - Text classification using Naive Bayes classifier
2.	First load the json file
3.	See the unique categories
4.	Give the category id for each category
5.	Draw the pie chart to show count of articles in each category
6.	We can plot bar graph to visualize the categories and number of headlines belonging to respective category
7.	We need to drop the columns which are not needed so that its easy to train.
8.	We can see the data, before and after cleaning.
9.	Data cleaning: This means to remove punctuations and covert to lower case
10.	We need to now filter the data
11.	Now we need to split the data into 80% Train, 20% Dev Data, 20% Test data
12.	We can also see the count of each headline in each category
13.	We need to separate features and targets
14.	Caculate the prior probabilities for two categories Crime and Entertainment
15.	We need to build vocabulary list
16.	We can use this vocabulary and create a dictionary
17.	We need to now find frequency/probability of each word - This is advantage of Naive Bayes
18.	Find conditional probability
19.	Find Top words of category = crime
20.	Find Top words of category = entertainment
21.	Since we got conditional probability, we will now find the prediction
22.	Split the dataset into given folds, use dev dataset.
23.	Find conditional probability with smoothing effect. This is advantage of Naive Bayes.
24.	Apply laplace smoothing
25.	Find prediction after smoothing. Draw graph to show effects after smoothing and comparing changes
