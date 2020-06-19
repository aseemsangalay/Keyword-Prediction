# Keyword Prediction

Demonstrating below on how to obtain the keywords from news articles.

## Libraries Used:
Pandas, pickle, re, nltk (stopwords, WordNetLemmatizer), sklearn (train_test_split, TFidFVectorizer, chi2), numpy

## Original content:

<img src="/IMG/1.png" alt="Step 1" widht="100 height="40">

The workflow is divided into 4 major steps:

## 1. Text cleaning:
    Special characters cleaning
    Uppercase to lowercase
    Removing punctuation signs
    Possessive pronoun
    Stemming and lemmatization
    Stopwords

	Content after Text Cleaning:

 	 <img src="/IMG/2.png" alt="Step 2" widht="100 height="40">


## 2. Label coding and modifying columns:
    News categories such as business, entertainment, politics, sports, tech are allotted codes (0,1,2,3,4) for the machine to     recognise them.

    Original Dataframe:

    <img src="/IMG/3.png" alt="Step 3" widht="100" height="40">


    Dataframe after Step 2:

    <img src="/IMG/4.png" alt="Step 4" widht="100" height="40">


## 3. Train-Test-Split:
  Separating training and testing dataset.


## 4. Text Representation:
	 Obtaining keywords for different categories of news. TFidFVectorizer is used along with
	 Chi2.After step 4, the result is as follows:


  	 <img src="/IMG/5.png" alt="Step 5" widht="100" height="40">
