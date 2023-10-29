# Sentiment-Analysis-of-Amazon-reviews

1. In this project, the sentiment analysis is performed on Amazon reviews using Python using two different techniques: 
      (a) VADER (Valence Aware Dictionary and sEntiment Reasoner) - Bag of words approach.
      (b) Roberta Pretrained Model from HuggingFace.
  
2. A dataset consisting of half a million records is taken as input which is in the form of a csv file.

3. Simple EDA is performed on the dataset to understand the dataset.

4. Next, Sentiment Analysis on the dataset is performed using VADER and the pre-trained transformer model 'Roberta'. Finally. the results are compared.

# Results

Both the models does the job of classifying the reviews as Negative, Neutral and Positive. But Roberta model is better performant than VADER sentiment analysis.

It's best to use Roberta model for sentiment analysis classification because VADER uses a Bag of words approach i.e., it gives the score for every word in the text and finally combines the scores of all the words to get a compound score of the text. VADER also doesn't consider the relationship of words present in the text which is quite important while performing sentiment analysis.
