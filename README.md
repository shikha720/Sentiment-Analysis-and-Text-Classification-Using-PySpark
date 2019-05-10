# Sentiment-Analysis-and-Text-Classification-Using-PySpark


Performing Sentiment Analysis on Amazon Fine food reviews and classifying the reviews into positive and negative Sentiment based on Review

```
## Environment and software
```
* Python
* JuPyter notebook
* PySpark

```
## Dataset
```
[Dataset](https://www.kaggle.com/snap/amazon-fine-food-reviews) can be downloaded from Kaggle.


## Steps involved
### 1. Importing Libraries
### 2. Creating SparkContext Object
### 3. Preparing Data
```
* a. Understanding Data and removing unwanted columns
* b. Filtering neutral reviews
* c. Assigning Positive and Negative Sentiment to Reviews based on Score
* d. Assigning Binary Rating as Target Variable 1: Positive 0: Negative
```
### 4. Text Pre-processing
```
* a. Create UDF Functions for text processing: Convert to lower case, Remove Punctuations and alphanumeric words, Remove Stop words
* b. POS tagging
* c. Text Lemmatization
* d. Assigning Binary Rating as Target Variable 1: Positive 0: Negative
```

### 5.Preparing Data For Modelling
```
* a. Creating Final Dataset with apt columns
* b. Dividing it into Training and Test Set
* c. Tokenizing the Training set anc creating TF-IDF matrix using HashingTF
```

### 6.Modelling data and Evaluating the Model 
```
* a. Logistic regression
* b. Naive Bayes
```


## Authors

* **Shikha Singh**
* **Sayoni Chatterjee**
* **Srishti Jaju**

