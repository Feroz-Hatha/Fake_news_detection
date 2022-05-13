# Fake News Detection Using Natural Language Processing (NLP)

In this project, we attempt to classify whether a piece of news is fake or not using the bag of words model for NLP. 

As NLP algorithms only work on numbers and not directly on text, we use the bag-of-words model to preprocess the text by converting it into a bag of words, disregarding grammar and even word order but keeping multiplicity. The model can be visualized in a tabular format, which contains the counts of individual words in the text. Before converting to this format, the text is cleaned by employing the re library designed to work with regular expressions. Conversion to the tabular format is achieved using the popular machine learning library sklearn. Once we have this tabular data, we have a binary classification problem in hand with the matrix of features being the count data, and we predict the target variable using various classfication algorithms. 

