# Information Retrieval Assignment
## Task Overview
Written for a third-year module. A skeleton program was provided, but code inside `my_retriever.py` is my own.
Python program to query a set of documents for relevance to terms in each query, and then return a list of hits. Similarity is computed according to 3 different weighting schemes - `binary`, `tf` (term frequency) and `tfidf` (term frequency multiplied by inverse document frequency)
- Binary
  - Hits depend upon whether search terms appear or not, unranked results
- TF
  - Results ranked based on how many times query terms appear in the document
- TFIDF
  - Common words such as "the", "as", "is", etc, can skew results in favour of certain documents. Multiplying the term frequency by the inverse document frequency serves to account for this bias.
  - `IDF = No. of documents in a collection ÷ No. of occurances of a word in a collection`
