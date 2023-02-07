# Sentiment Analysis
- Compared two sentiment analysis modelsL LSTM and VADER. 
- Implemented on the Amazon food review data set from Kaggle, using NLTK, SKlearn and TensorFlow libraries.
- Used evaluation metrics such as: confusion matrix, precision, recall, F1-Score, and accuracy, with LSTM model outperforming VADER.

**Access the project using this [link](https://github.com/jahnsite/SentimentAnalysis/blob/main/Sentiment%20Analysis.ipynb)**

## Background Information

- “Have you tried the chocolate cake? It’s really good!” is a piece of text that can be easily determined as a positive food review. While this can be easily deduced by a human, sentiment analysis is the process of computationally identifying and categorising text to determine the overall opinion of the piece of text – positive, negative or neutral.

- It is a powerful tool that can be used to predict stock prices and enhancing customer experience. For example, a company can use sentiment analysis to gauge customer attitudes to a product/service, and this can be done automatically without having to manually read all of them. If the sentiment is overwhelmingly negative, the company can understand why the customers have a less liking to the product or service and how they can increase the customer reviews.

- One of the obvious downsides to sentiment analysis is that it ignores the themes and nuances present in the text and gives a polarised output – positive or negative.

- There are two approaches to sentiment analysis – lexicon-based approach and machine learning approach.

### Lexicon-based Approach
 
- Also called a rule-based approach, it uses a dictionary of words along with their polarity. The polarity value can range from -1 to 1, that is, from positive to negative. For example, words like ‘great’ and ‘fantastic’ are given the integer value of 1 denoting a positive sentiment, whereas, words like ‘terrible’ and ‘gross’ are given the integer value -1 denoting a negative sentiment. The polarity value for each word is added and divided by the number of words in the text.

- The simplicity and easy accessibility of the sentiment attached to the words is one of the advantages of using this approach. However, there can be missing words, furthermore, one could be at a disadvantage when using this method for other languages than English due to the lack of extensive vocabulary in the dictionary. Another disadvantage is that is cannot detect context. Therefore, a positive word according to the dictionary could be in the context of sarcasm, which in reality would denote a negative sentiment.

### Machine Learning Approach

- When using a machine learning approach, one needs classified training data. The said algorithm is then trained on this data, in order to predict the classification of unseen data. This approach depends on the type of algorithm and the kind of the training data used.

- There are many kinds of machine learning (ML) and deep learning (DL) algorithms, such as the Naïve Bayes algorithm and the DeepForest method each with their own niches. In this project I focused on an extension of a Recurrent Neural Network called the LSTM or the Long Short-Term Memory.

- Some of the advantages of ML/DL models is that, firstly, these complex algorithms are capable of learning from data and the accuracy of the predictions increases when more training data is provided. Secondly, they are good at identifying patterns and trends in huge amounts of data which would otherwise be very time consuming.

- Acquiring proper data and selecting the appropriate algorithm for the problem is one of the major disadvantages of using a machine learning approach. Furthermore, processing such huge amounts of data is very time consuming. 

**In the context of this paper – a lexicon-based model (VADER) has been compared with a machine learning approach (LSTM).**



