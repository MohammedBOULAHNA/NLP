# NLP
Natural language processing (NLP) is a field that focuses on making natural human language usable by computer programs. NLTK, or Natural Language Toolkit, is a Python package that you can use for NLP.

## 1.Basic NLP:

- ***Presentation of NLTK*** : The first thing you need to do is make sure that you have Python installed. Once you have that dealt with, your next step is to install NLTK with pip.
![image](https://user-images.githubusercontent.com/124175118/217586014-17961a8c-2ecc-4782-8999-fa16b7680d33.png)

 
- ***Tokenization:*** The segmentation of text and the task of subdividing the text into small units that will be easier to process and that we call tokens.
The nltk library offers through the tekenize module a number of tokinzers that allow to perform the segmentation of the text according to the nature of the problem: words tokenizer, regular-expression based tokenizer, sentences based tokinizers, etc. Below is a non-exhaustive list of some functions of the tokinize module. 

- *regexp_span_tokenize(text, regexp): Returns the text tokens that match the regular expression regexp*
- *sent_tokenize(text[, language]):	Returns the phrases contained in the text using the PunktSentenceTokenizer tokenizer*
- *word_tokenize(text[, language]:	Returns the words contained in the text using the TreebankWordTokenizer tokenizer with PunktSentenceTokenizer.* 

*nltk* offre également un certain nombre de classes qui offrent des tokinizers plus avancés : BlanklineTokenizer, MWETokenizer, PunktSentenceTokenizer, TextTilingTokenizer, TweetTokenizer, etc. 
<img width="900" alt="image" src="https://user-images.githubusercontent.com/124175118/217589328-30c2a3cb-4a32-4734-a18a-bba3c270e47a.png">


- ***Stemming:*** Stemming is a text processing task in which you reduce words to their root, which is the core part of a word. For example, the words “helping” and “helper” share the root “help.” Stemming allows you to zero in on the basic meaning of a word rather than all the details of how it’s being used. NLTK has more than one stemmer, but you’ll be using the Porter stemmer.

-  ***Lemmatization*** : Now that you’re up to speed on parts of speech, you can circle back to lemmatizing. Like stemming, lemmatizing reduces words to their core meaning, but it will give you a complete English word that makes sense on its own instead of just a fragment of a word like 'discoveri'.
-   ***POS-tagging*** : Pos-tagging allows to perform a lexical analysis of a text expression according to the rules of grammar. The different units will be provided with an annotation allowing to know the grammatical role of each word in the expression. The most common annotations are (DT: Determiner, NN: noun, JJ: adjective, RB: adverb, VB: verb, PRP: Personal Pronoun...).




## 2. Plagiat_detection (Syntactic_Semantic_ similarities_between_Documents)

- WSD
- Bag of Words
- TF-IDF
- LSA/SVD
- Word2vec
- GloVe


## 3. Clustering Document 

- Feature selection
- Clustering models
- Model evaluation


## 4. Classification Document

- Feature selection
- Classification Models
- Model evaluation



## 5.Topic Mining

• Unigram Language Model
• LSA
• LDA

## 6.Transfer Learning NLP TF Hub

Transfer Learning for NLP with TensorFlow Hub

This project/notebook consists of several Tasks.
- Task 1: Introduction to the Project.
- Task 2: Setup your TensorFlow and Colab Runtime
- Task 3: Download and Import the Quora Insincere Questions Dataset
- Task 4: TensorFlow Hub for Natural Language Processing
- Task 5: Define Function to Build and Compile Models
- Task 6: Define Function to Build and Compile Models(Continued...)
- Task 7: Train Various Text Classification Models
- Task 8: Compare Accuracy and Loss Curves
- Task 9: Fine-tuning Models from TF Hub
- Task 10: Train Bigger Models and Visualize Metrics with TensorBoard

## 7. ABSA with_Spacy and TextBlob Sentiment analysis:
- TextBlob est une bibliothèque qui propose une analyse des sentiments prête à l'emploi. Il a une approche par sac de mots, ce qui signifie qu'il a une liste de mots tels que «bon», «mauvais» et «excellent» qui ont un score de sentiment qui leur est attaché. Il est également capable de sélectionner des modificateurs (tels que «not») et des intensificateurs (tels que «very») qui affectent le score de sentiment. 

## 8. Logistic Regression based sentiment analysis :
* Extract features for logistic regression 
* Implement logistic regression from scratch
* Apply LR for sentiment analysis 
* Test your model 
* error analysis
## 9. IMDB-LSTM with CNN : 
- This is a dataset of 25,000 movie reviews from IMDB, labeled by sentiment (positive / negative). The reviews have been pre-processed and each review is coded as a list of (integer) word indexes. For convenience, the words are indexed by their overall frequency in the dataset, so that, for example, the integer "3" codes the 3rd most frequent word in the data. 

## 10. Exploring Data.
