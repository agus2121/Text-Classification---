# Text-Classification---hotel-reviews

## Dataset

Source: https://www.kaggle.com/ilhamfp31/dataset-tripadvisor

11696 rows and 2 columns(text,sentiment). Sentiment consist two class: Positive and Negative

## Step

1. Getting the Data
2. Preprocessing text (drop duplicates, remove punctuation, take alphabet and numeric only, remove stopwword and remove word less than three characters)
3. create some wordcloud
4. convert using TFIdf Vectorizer
5. Modelling with Naive Bayes(MultinomialNaiveBayes)
6. predict test_data and evaluation with confusion matrix
7. Predicting new data

## Reference:

[1] A. N. Farhan & M. L. Khodra. “Sentiment-specific word embedding for Indonesian sentiment analysis”. In: 2017 International Conference on Advanced Informatics, Concepts, Theory, and Applications (ICAICTA). 2017, 1–5. DOI: 10.1109/ICAICTA.2017.8090964. URL: https://www.kaggle.com/ilhamfp31/dataset-tripadvisor

[2] Python Sastrawi. URL : https://github.com/har07/PySastrawi
