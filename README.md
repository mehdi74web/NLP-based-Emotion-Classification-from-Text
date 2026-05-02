# NLP-based-Emotion-Classification-from-Text
This project implements a Natural Language Processing (NLP) pipeline to classify text into six distinct emotional categories: sadness, anger, love, joy, fear, and surprise. Using a dataset of 16,000 records, the model accurately maps complex human sentiments to numerical labels for machine learning analysis.
Key Features
Comprehensive Preprocessing: Custom cleaning pipeline to handle noise like punctuation, digits, URLs, and non-ASCII emojis.  

NLTK Integration: Efficient removal of English stopwords and precise tokenization.  

Vectorization: Implementation of CountVectorizer (Bag of Words) to transform raw text into a machine-readable format.  

Probabilistic Modeling: Leverages the Multinomial Naive Bayes algorithm, ideal for discrete feature counts in text classification.  

Tech Stack
Language: Python  

Libraries: Scikit-learn, NLTK, Pandas, NumPy, Matplotlib, Seaborn
