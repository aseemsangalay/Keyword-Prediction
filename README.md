# Keyword Prediction

Demonstrating below on how to obtain the keywords from news articles.

## Dependencies Used:
- Pandas
- numpy
- pickle
- re
- nltk (stopwords, WordNetLemmatizer)
- sklearn (train_test_split, TFidFVectorizer, chi2)

## Original content:

![Step1](/IMG/1.png)

The workflow is divided into 4 major steps:

## 1. Text cleaning:
   Special characters cleaning
   Uppercase to lowercase
   Removing punctuation signs
   Possessive pronoun
   Stemming and lemmatization
   Stopwords

   Content after Text Cleaning:
   ![Step2](/IMG/2.png)


## 2. Label coding and modifying columns:
   News categories such as business, entertainment, politics, sports, tech are allotted codes (0,1,2,3,4) for the machine to      recognise them.

   Original Dataframe:

   ![Step3](/IMG/3.png)


   Dataframe after Step 2:

   ![Step4](/IMG/4.png)


## 3. Train-Test-Split:
   Separating training and testing dataset.


## 4. Text Representation:
   Obtaining keywords for different categories of news. TFidFVectorizer is used along with Chi2.
   After step 4, the result is as follows:
   
   ![Step5](/IMG/5.png)
