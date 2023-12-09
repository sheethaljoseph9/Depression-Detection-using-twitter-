# Depression Detection using twitter.
Major depression constitutes a serious challenge in personal and public health. Tens of millions of people each year suffer from depression
and only a fraction receives adequatetreatment. We explore the potential to use social media to detect and diagnose major depressive disorder in individuals.
The goal of this project is to examine automatically analysing the social media textual data (Twitter) using Natural Language Processing (NLP) and Machine learning (ML) techniques to detectsigns of depression. In this project, several supervised machine learning algorithms (such as NB, SVM, RF) with feature engineering techniques are used and compare their results with those of transformer based deep learning pre-trained model (distilBERT). Feature extraction is done using term frequenverse document frequency (TF-IDF) and Bag of Words (BoW) model. Since the neural networks cannot deal with tweets directly, used a well-known word embedding technique called Word2vec by Google for the vector representation.

# About The Project 
The project can be divided into 5 step process:

- Step 1: Gathering Data
* Step 2: Cleaning Data
+ Step 3: Data Analysis
- Step 4: Model
* Step 5: Testing and Analysing Model

# Step 1: Gathering Data 
The csv file contains manual labeling of sentiment words and manual analysis of sentiment. This has been recorded along with a sentiment analyser's output. https://www.kaggle.com/gargmanas/sentimental-analysis-for-tweets

# Step 2: Cleaning Data
 - Removing stop words
 * Lemmatization (Coverting to Root Words)
 + Removing non-word charecters, single charecter, spaces , URLs, etc.
 
 # Step 3: Data Analysis
  - WordCloud on Negative Tweets
  * WordCloud on Positive Tweets
  
 # Step 4: Model
  - Vectorizing input to input into model
  * Model Chosen: Naive Bayes, Support Vector Machine, Random Forest, DistilBERT
  
 # Step 5: Testing and Analysing Model
 The performance of the models are evaluated with the help of accuracy, recall, precision and f-scores.
