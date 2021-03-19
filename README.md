# Text-classification-NLP

spam dataset used: https://www.kaggle.com/uciml/sms-spam-collection-dataset

Task is to to get a best possible classifier for text classification.

Approach:

first of all, removed unnamed columns and updating relevant naming to other columns.

then performed data Cleaning and Preprocessing by making text lowercase, remove text in square brackets,remove links,remove punctuation and remove words containing numbers.

Applied different vectorizers like,

Count Vectorizer : Count Vectorization is used for counting the number of occurrences each words appears in a document (like various text such as an article, book, paragraph). Python’s Sci-kit learn library has a tool named as CountVectorizer to implement this.

TF-IDF Vectorizer : TF-IDF is a short form of Term Frequency Inverse Document Frequency. This algorithm is used to transform text into a meaningful representation of numbers which is used to fit machine algorithm for prediction.

Hashing Vectorizer : Hash functions are an efficient way of mapping terms to features. This algorithm a hashing function to term frequency counts in each document, where TfidfVectorizer scales those term frequency counts in each document by penalising terms that appear more widely across the corpus.

Also, used machine learning techniques like Logistic Regression, Multinomial Naive Bayes, Support Vector Machine (SVM) to get accuracy score.

