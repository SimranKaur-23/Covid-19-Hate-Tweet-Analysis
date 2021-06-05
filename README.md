# Covid-19-Hate-Tweet-Analysis
  - this task was performed as a part of an academic case study on NLP.
  - performed analysis on hate tweets and offensive tweets.
  - the dataset is provided as *climate.csv* file.
## A gist of what i did...
  - imported the necessary libraries.
  - read the dataset.
  - used functions like info(), describe(), isnull() to know more about the dataset.
  - used pie plot to show the distribution of class.
  - cleaned the tweets and added a new column with the name tidy_tweets which contains these clean tweets.
  - removed punctuations, numeric and stopwords from tidy_tweets.
  - next i tokenized and stemmed these tweets in tidy_tweets.
  - next i made a function to make a word cloud of these tidy_tweets and diplayed the word cloud on screen.
  - made separate datafarmes for hate tweets, offensive tweets and tweets which are neither of the two and displayed their word clouds on screen.
  - made a function to find hashtags and then found hashtags from dataframe containing hate tweets, offensive tweets and neither of the two.
  - next, found out the word frequency of each hashtags in these dataframes.
  - displayed a plot of these hashtags using barplot.
  - extracted features from clean tweets using bag of words word embedding. Made a bag-of-words feature matrix and displayed this matrix on screen.
  - next i split the data into training and validation set and used xgboost and linear regression as classifiers to find out the f1-score of these models.
  - Next, i made a comoarison table which contains the f1-score of these two models and then plotted these scores to visualize the comparison.
