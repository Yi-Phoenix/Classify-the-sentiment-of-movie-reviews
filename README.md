# Classify-the-sentiment-of-movie-reviews
## Introduction
  Sentiment is a thought, opinion, or idea based on a feeling about a situation, or a way of thinking about something. Sentiment classification is a challenging classification task, which uses natural language processing, text analysis, computational linguistics, and biometrics to identify opinions and emotions in text and assign proper sentimental labels (such as positive, negative, or neutral) to them. Sentiment classification has been widely used in business and product development settings to understand how customers feel about products, services, or brand. The objective of this project is to conduct sentiment classification on the Rotten Tomatoes dataset using a variety of classifiers and evaluate/compare the prediction results. 
## Dataset
  The Rotten Tomatoes movie review dataset (accessible at: https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews) contains a corpus of movie reviews used for sentiment analysis, which is originally collected by Pang and Lee (2006). Later, Socher et al. (2013) created fine-grained labels for all parsed phrases in the corpus using Amazon's Mechanical Turk. As a result, the text in Rotten Tomatoes dataset is not complete sentences but parsed short phrases. The dataset includes a total of 156,060 training data and 66,292 testing data. The training set has 4 columns: PhraseId, SentenceId, Phrase, and Sentiment, while the test set has the first three but no Sentiment. The first ten training samples are shown in Table 1. The length of each phrase varies, and some phrase may just contain one stop word (e.g., phrase 4 and 7) or one punctuation. However, the same stop word may have very different labels, leading to a certain challenge in this data set.
  The training data are classified into 5 classes, which are 0-negative, 1-somewhat negative, 2-neutral, 3-somewhat positive, 4-positive. There is a natural order among the different classes. Such ordering information can be used during the classification task. Notably, neutral is the dominant class whose number of data points is over 10 times than the number of data points from the most minor class (negative; Figure 1). 
  
