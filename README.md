# customer-review-sentiment-analysis
NB: the concept and tasks requirements were set by Forage as part of a preskilling task for British Airways.

Using senitment analysis to classify customer reviews, conduct analysis and gain insights.

workflow was as follows:
1. scaped the reviews from a airline reviews website (using beautfulSoup library)
2. inspected and conducted EDA on the data
3. used the scores associated with the reviews to classify the data into positive, neutral and negative
4. cleaned the data (e.g. removing puntuation, special characters, numbers, stopwords etc.) + applying word stemming
5. split the data into train and test (80:20 split). Chose not to train/test on reviews classfied as neutral (data was split after "removing" neutral reviews)
6. tested 3 different models: logistic regression, support vector machine and naive bayes whilist also testing the effect of using unigrams, bigrams, trigrams and a mixture of all 3 (found Naive Bayes with unigrams gave the best performance/accuracy)
7. used the model to classify the reviews (including "neutral" reviews)
8. conducted further analysis and made visualizations to present insights from the data

