# sentiment-analysis-yelp-review

# Steps :-

1) Downloaded and Loaded the yelp.csv and ran some basic functions like head() , info() , describe()
2) Added a new column text_length that contains character count of text column.
3) Used Seaborn to display various visualizations related to the DataSet
4) Seperated the 1-Star and 5-Star reviews and stored it into a new DataFrame.
5) Performed Text-Preprocessing on the new DataFrames text column to remove punctuations and stopwords.
6) Used CountVectorizer to extra bag-of_words for the DataFrame.
7) Seperated the DataSet into Traning and Testing DataSet.
8) Applied a Multinomial Navie Bayes Model on the Traning Set.
9) Tested the model on a Test DataSet ( The model has 92% Accuracy)
10) Checked the accuracy of the model on a single positive and a single negative review.  [Accurately predicts some. but the model fails when the review has too many words or a negative review contaings positive words such as Happy, etc.]
