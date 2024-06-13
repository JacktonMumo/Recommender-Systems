# Recommender Systems
## Content-based recommenders
* we will incorporate NLP in this system so that we can put our text in numerical representation
### difference between CountVectorizer and sentence_transformer
* countVectorizer - creates numerical representation of text based on word frequency(how many times each word appears). it is commonly used in tasks like sentiment analysis(positive or negative), document classification(spam or not spam), topic modelling(identify themes in a collection of documents)
* sentence - transformers - Generates dense vector embeddings that capture the sentiment of a sentence. these embeddings go beyond word frequency and aim at representing the overall meaning and relationship between words in a sentence. it is used with advanced sematic tasks like content based recommenders, finding similar sentences, sematic search(retrieving documents with similar meaning)
* in DistilBERT-base - this is a function that is the underlying architecture of the pre-trained model used for sentence encoding.
* fine-tune for nli(Natural Language Inference) - helps the model to capture sematic similarities and relationships between sentences, eg sentence B implies sentence A, sentence B is the opposite of sentence A
* STS-B (Sematic Textural Similarity Benchmark) : the dataset helps to model learn encoded sentences in a way that reflects their similar meaning and how they are to each other
* mean token - splits sentence into words and finds their meaning