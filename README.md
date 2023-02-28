# Amazon-Product-Reviews-Sentiment-Analysis
The project is to analyze the dataset of the reviews and check it sentiment of prediction over different machine learning models. 
The target is to analyze the sentiment of negative and positive classes. 
Here we have used the model of Gaussian Naïve Bayes, Random Forest, ANN, Ensemble method and the Lexicon.

# Dataset
Dataset is downloaded from the website named Kaggle  In which we have the data of a long list of reviews and their rating Scores. 
The rating greater than 3 is consider to be the positive sentiment and less then of equal is consider to be the negative sentiment. 
This dataset contains of 568454 records of 10 columns.

# Data preprocessing
For the sentiments, we just need the target sentiment label and review text so we have taken these two columns. 
After this, we need to apply some preprocessing over the text reviews. 
For this, we applied some functions that will remove links, tags, and special characters and remove the noise from the text like stopwords. 
Then we applied the count vectorizer to convert the text into arrays with the maximum vector length of 50 instances. 
After this we splitted the text into train and test data. The train data contains 397917 records and test data contains 170537 records.

# Models Comparisons
Here are model comparison graph that show that the model have performed well is the random forest classifier model and shows the good then any other model. 
So this model is taken to be the best model for this problem.


![image_2023_02_28T08_52_28_098Z](https://user-images.githubusercontent.com/68701684/221802578-1827da58-be17-49ba-b8ab-0cc9fe2a92df.png)
