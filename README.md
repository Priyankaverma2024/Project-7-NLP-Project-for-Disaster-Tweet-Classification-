# Project-7-NLP-Project-for-Disaster-Tweet-Classification-
Natural Language Processing(NLP)
Disaster-related tweets have the potential to alert relevant authorities early on so that they can take action to reduce damage and possibly save lives.

In this project, we attempt to predict whether a given tweet indicates a real disaster or not.
A detailed exploratory data analysis on the dataset is carried out .
I consider a number of text normalization processes,namely conversion to lowercase,removal of whitespaces,removal of punctuations,removal of unicode characters(including HTML tags,emojis,and URLs starting with htttp),subtitutes of contractions,removal of stop words,spelling correction,stemming,lemmatization,discardment of non-alphabetic words,and retention of relevant part of speech.
Here I implement bag of words text representation and extend the analysis to bag of unigrams,bigrams,trigrams as well as mituer representation incorporating all words and all grams.
Next , i implement TF-IDF text representation. Similar to the previous setup, we carry out unigram, bigram, and trigram analysis.
For each text representation setup, we apply a number of classifiers, namely logistic regression, randomforest classsifier, support vector machine,Nomialbaised classification,Xgboost classifieretc, Voting classifier. and compare their performances in terms of the average F1-score,accuracy obtained from classification report .
finally voting classifier gives the best accuracy (83% )to predict real or fake tweets.
