# NLP
Natural language processing (NLP) is a field that focuses on making natural human language usable by computer programs. NLTK, or Natural Language Toolkit, is a Python package that you can use for NLP.

## 1.Basic NLP:

- ***Presentation of NLTK*** : The first thing you need to do is make sure that you have Python installed. Once you have that dealt with, your next step is to install NLTK with pip.
![image](https://user-images.githubusercontent.com/124175118/217586014-17961a8c-2ecc-4782-8999-fa16b7680d33.png)

 
- ***Tokenization:*** The segmentation of text and the task of subdividing the text into small units that will be easier to process and that we call tokens.
The nltk library offers through the tekenize module a number of tokinzers that allow to perform the segmentation of the text according to the nature of the problem: words tokenizer, regular-expression based tokenizer, sentences based tokinizers, etc. Below is a non-exhaustive list of some functions of the tokinize module. 

- *regexp_span_tokenize(text, regexp): Returns the text tokens that match the regular expression regexp*
- *sent_tokenize(text[, language]):	Returns the phrases contained in the text using the PunktSentenceTokenizer tokenizer.
- *word_tokenize(text[, language]:	Returns the words contained in the text using the TreebankWordTokenizer tokenizer with PunktSentenceTokenizer.* 

*nltk* offre également un certain nombre de classes qui offrent des tokinizers plus avancés : BlanklineTokenizer, MWETokenizer, PunktSentenceTokenizer, TextTilingTokenizer, TweetTokenizer, etc. 

- Stemming , Lemmatization , POS-tagging, Parsing.
