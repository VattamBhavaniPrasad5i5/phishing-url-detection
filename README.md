# PHISHING-URL-DETECTION
The purpose of Phishing Domain Detection is detecting phishing domain names. Therefore, passive queries related to the domain name, which we want to classify as phishing or not, provide useful information to us. 
I dropped dulicates because URLs are uniqic from each other
I used some technique like tokenizer ,count vectorizer
# TOKENIZER
The tokenize module provides a lexical scanner for Python source code, implemented in Python. The scanner in this module returns comments as tokens as well, making it useful for implementing “pretty-printers”, including colorizers for on-screen displays.
In this process i used to remove '/','.' like symbols from urls because these are common for all genuine urls and phished urls.
After applied tokenizer all urls are free from '/' and '.'
# COUNT VECTORIZER and TFIDF
CountVectorizer is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text.
CountVectorizer creates a matrix in which each unique word is represented by a column of the matrix, and each text sample from the document is a row in the matrix. The value of each cell is nothing but the count of the word in that particular text sample.
TF-IDF is an abbreviation for Term Frequency Inverse Document Frequency. This is very common algorithm to transform text into a meaningful representation of numbers which is used to fit machine algorithm for prediction. Let’s take sample example and explore two different spicy sparse matrix before go into deep explanation . 
Term Frequency (tf)- It gives us the recurrence of the word in each report in the corpus. It is the proportion of the number of times the word shows up in a report contrasted with the all-out the number of words in that record. It increments as the quantity of events of that word inside the record increments.
Inverse Data Frequency (idf)- It is used to figure out the heaviness of uncommon words over all reports in the corpus. The words that occur seldom in the corpus have a high IDF score.
# MULTINOMIAL NATIVE BAYES
Naive Bayes Classifier Algorithm is a family of probabilistic algorithms based on applying Bayes’ theorem with the “naive” assumption of conditional independence between every pair of a feature.
Naive Bayes are mostly used in natural language processing (NLP) problems. Naive Bayes predict the tag of a text. They calculate the probability of each tag for a given text and then output the tag with the highest one. 
Naive Bayes classifier for multinomial models. The multinomial Naive Bayes classifier is suitable for classification with discrete features (e.g., word counts for text classification). The multinomial distribution normally requires integer feature counts.
# FLASK
Flask is a web framework that provides libraries to build lightweight web applications in python. It is developed by Armin Ronacher who leads an international group of python enthusiasts (POCCO). It is based on WSGI toolkit and jinja2 template engine.
Flask is a web framework, it’s a Python module that lets you develop web applications easily. It’s has a small and easy-to-extend core: it’s a microframework that doesn’t include an ORM (Object Relational Manager) or such features.
