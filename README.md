# Road-to-Data-Science

Advanced NLP with Python for Machine Learning

Bookmark: https://www.linkedin.com/learning/advanced-nlp-with-python-for-machine-learning/what-is-word2vec?autoSkip=true&resume=false&u=3322

Covers advanced NLP with Python, cleaning and vectoring data, word2vec, and neural networks.

The special skills recommended for this course are NumPy, pandas, and scikit-learn.

Jupyter Notebooks combine live code, explanatory text, visualizations, and equations in one package. They are an open document format based on JSON, which provides explanations and visuals for help.

Natural Language Processing (NLP)
Field concerned with the ability of a computer to understand, analyze, manipulate, and potentially generate human language.

NLP is a subset of artificial intelligence (AI).

NLP is used in:
- Search engines
- Spam filters
- Voice-activated assistants
- Machine translation
- Chatbots
- Sentiment analysis
- Spell checkers
- Grammar checkers
- Fraud detection
- Market intelligence
- sentence segmentation or part-of-speech tagging


Lambda function:
- A function that is defined without a name.
- Also known as an anonymous function.
- Can take any number of arguments, but can only have one expression.
- The expression is evaluated and returned.
- Lambda functions can be used wherever function objects are required.
- Lambda functions are syntactically restricted to a single expression.
- Semantically, they are just syntactic sugar for a normal function definition.
- Like nested function definitions, lambda functions can reference variables from the containing scope.
- print(lambda x: x + 1)

Term Frequency-Inverse Document Frequency (TF-IDF)
- A numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus.
- Used as a weighting factor in information retrieval and text mining.
- The TF-IDF value increases proportionally to the number of times a word appears in the document and is offset by the number of documents in the corpus that contain the word.
- Used for search engine scoring, text summarization, and document clustering.
- TF-IDF is the product of two statistics, term frequency and inverse document frequency.
- TF-IDF is a measure of originality, not frequency.
- TF-IDF is computed as follows:
  - TF(t) = (Number of times term t appears in a document) / (Total number of terms in the document)
  - IDF(t) = log_e(Total number of documents / Number of documents with term t in it)
  - TF-IDF(t) = TF(t) * IDF(t)
- TF-IDF is high when the term occurs many times in a document, but is offset by the frequency of the word in the corpus.
- TF-IDF is low when the term occurs fewer times in a document, but is offset by the frequency of the word in the corpus.

Instantiating
- Instantiating a class means creating an instance of that class.
- Instantiating a class means calling the constructor of the class.
instantiating a vectorizer:
- vectorizer = TfidfVectorizer(analyzer = yourtextpreprocessingfunction)

TF-IDF vectorizer outputs a sparse matrix:
- A matrix in which most of the elements are zero.
- In contrast, if most of the elements are nonzero, then the matrix is considered dense.
- The number of zero-valued elements divided by the total number of elements is called the sparsity of the matrix.
- only stores the location of non-zero elements.





