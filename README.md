# Spam-Email-Detection

DESCRIPTION:
Detecting spam emails using logistic regression in Python involves building a machine learning model that can classify emails as spam or not spam based on certain features.

ALGORITHM USED: Logistic Regression

Logistic regression is a commonly used algorithm for binary classification tasks like spam detection.Logistic regression is a statistical method that is widely used for binary classification problems, such as spam email detection. In the context of spam email detection, the goal is to build a model that can classify emails into two categories: spam or not spam (ham).

PACKAGES USED:
1) TfidfVectorizer :
   The TfidfVectorizer is a feature extraction method commonly used in natural language processing and text mining. It is part of the scikit-learn library in Python. "TF-IDF" stands for Term Frequency-Inverse Document Frequency, and it is a numerical statistic that reflects the importance of a word in a document relative to a collection of documents (corpus).
   
Term Frequency (TF): Measures how often a word appears in a document. It is calculated as the number of times a word appears in a document divided by the total number of words in that document.
    TF(t,d)= Total number of terms in document d / Number of times term t appears in document d

Inverse Document Frequency (IDF): Measures the importance of a word in the entire corpus. It is calculated as the logarithm of the total number of documents divided by the number of documents containing the term, plus 1.
   IDF(t,D)=log(Total number of documents in the corpus N / Number of documents containing term t+1 )+1

TF-IDF: The product of TF and IDF, providing a weight to each term in each document.
​   TF-IDF(t,d,D)=TF(t,d)×IDF(t,D)

2)TfidfTransformer :
   The TfidfTransformer is another component in scikit-learn that, like TfidfVectorizer, is used for transforming a count matrix to a normalized term-frequency or term-frequency times inverse document-frequency (TF or TF-IDF) representation.

3)CountVectorizer:
   CountVectorizer is a feature extraction method in scikit-learn that is used to convert a collection of text documents to a matrix of token counts. It essentially transforms a set of text documents into a numerical format suitable for machine learning algorithms. 
