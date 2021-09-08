####################################
File Guide

presentation.ipynb - Final report for the project. Contains the code, viz, explanations of the project

word2vec.fullmodel - Word vector created from spongebob dialogue. Can only open if you have package "gensim"

transcripts.json - Dictionary containing each line of dialogue for the episodes scraped. Dialogue tokenized but 
	no other processing done.

Rlinmod_out.PNG - picture of R output for linear regression model

heatmap char ints.png - heatmap of character interactions

heatmap char avg.png - heatmap of directional sentiment

writers.csv - one-hot encoded writers

text.csv - dataset used for second part of ratings prediction, has 3 classes : 'better','good','bad'

nb1.csv - dataset used for first part of ratings prediction, has only two classes : 'good','bad'


###################################
Required Packages

gensim, spacy, nltk, pyspark, 


###################################
Interacting with the Code

The code can be run all the way through using the included files.