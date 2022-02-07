# Naive-Bayes-Classifier
Implemented a naïve bayes classifier that classifies advertisements in 6 different categories.

## Description
The objective of this project is to build a naïve bayes classifier that classifies advertisements for second-hand items in categories vehicles, electronic devices, buisinees, for the home, personal, leisure and hobbies. Each advertisement has the following properties:<br />
title, description, categories<br />

For extracting features from title and description, the following steps were taken:<br />
1) Tokenizing
2) finding the words with too many repetitions and omitting them.
3) Omitting the stop words
4) Stemming and lemmatization

In the end, probabilities were calculated with and without using **additive smoothing** and the results were compared.
