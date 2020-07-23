
Word2vec : 

There are 2 model variants
- SG -> Skip-Grams
    - the distributed representation of the input word is used to **predict the context**.
    - works well with a small amount of the training data, represents well even rare words or phrases.
- CBOW -> Continous Bag of Words
    - the distributed representations of context (or surrounding words) are combined to **predict the word** in the middle.
    - several times faster to train than the skip-gram, slightly better accuracy for the frequent words.

We want to represent words in such a manner that it captures its meaning in a way humans do. Not the exact meaning of the word but a contextual one.
