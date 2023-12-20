# Depression Detection using Twitter.
Major depression constitutes a serious challenge to personal and public health. Tens of millions of people each year suffer from depression
and only a fraction receives adequate treatment. We explore the potential to use social media to detect and diagnose major depressive disorder in individuals.
The goal of this project is to examine automatically analyzing the social media textual data (Twitter) using Natural Language Processing (NLP) and Machine learning (ML) techniques to detect signs of depression. In this project, several supervised machine learning algorithms (such as NB, SVM, RF) with feature engineering techniques are used and compare their results with those of transformer-based deep learning pre-trained models (distilBERT). Feature extraction is done using the Term Frequency- Inverse Document Frequency(TF-IDF) and Bag of Words (BoW) model. Since the neural networks cannot deal with tweets directly, used a well-known word embedding technique called Word2vec by Google for the vector representation.

# About The Project 
The project can be divided into 5 step process:

- Step 1: Gathering Data
* Step 2: Data Preprocessing
- Step 3: Data Visualization
- Step 4: Feature Engineering
- Step 5: Model Training
* Step 6: Testing and Analysing Model

# Step 1: Gathering Data 
The CSV file contains manual labeling of sentiment words and manual analysis of sentiment. This has been recorded along with a sentiment analyzer's output. https://www.kaggle.com/gargmanas/sentimental-analysis-for-tweets. The dataset contains 10000 tweets scrapped from Twitter and each tweet is given a label 1 or 0: 1 denotes people with symptoms of depression while 0 denotes that the user does not.

# Step 2: Data Preprocessing
 - Removing stop words and punctuations
 * Lemmatization (Converting to Root Words)- For example, 'connected', 'connection', and 'connecting' can be reduced to 'connect
 + Removing special characters, hashtags, links, emojis and URLs.
 + Expanding contracted text- 'can't' is converted to cannot and 'hungryyyy' is converted to 'hungry'.
 
 # Step 3: Data Visualization
  - Dataset label count
  - WordCloud on Negative Tweets
  * WordCloud on Positive Tweets
  
 # Step 4: Feature Engineering
 The different methods of feature extraction used in this project are as follows:
 - Bag of Words(BoW)- describing a document as a collection of its words.
 - TF-IDF Vectorizer- each word in a text is given a weighted significance score depending on how frequently it appears in the document and how uncommon it is within the corpus of documents.
 - Word Embeddings(Word2Vec)- capturing the semantic meaning of words and links to other words including synonyms, antonyms, and related ideas.

# Step 5- Model Training
Some traditional methods are used to perform text classification and each feature extraction is trained on each model. The models are:
- Naive Bayes
- Random Forest
- Support Vector Machine.
- distilBERT, a transformed-based deep learning pre-trained model which is a subset of BERT.

# Step 5: Testing and Analysing Model
 The performance of these models is evaluated with the help of accuracy, recall, precision, and f-scores. We conclude that distil, Random Forest and SVM models are the best-performing
 models after comparing the f-scores of the models. Compared to conventional machine learning algorithms, BERT performs better as it captures more sophisticated linguistic elements and 
 contextual links in text data. 
