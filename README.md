# Fake-News-Prediction

#### I collected the dataset from [here](https://www.kaggle.com/c/fake-news/data?select=train.csv).

## Problem Statement :

  This is a kind of classification problem where we need to identify unreliable news articles.
  
  The goal is to predict that a news is Fake or Real.
  
## Dataset Descriprion:

  The dataset with the following attributes:

    * id: unique id for a news article
    * title: the title of a news article
    * author: author of the news article
    * text: the text of the article; could be incomplete
    * label: a label that marks the article as potentially unreliable
                1: unreliable i.e. Fake
                0: reliable i.e. Real
                
 ## Procedure followed for this experiment:
    
### 1. Dataset loading and preprocessing of dataset:
      * Importing different libraries like numpy, pandas, sklearn etc.
      * Importing the nltk library and downloading the stopwords.
      * Verifying the null values in the dataset.
          ** As we have the dataset with huge 20800 records , so deleting the null values will not hamper.
          ** So, we replacd the null values with empty string.
      * 
 
