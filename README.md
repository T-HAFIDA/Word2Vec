# Word2Vec
#### We used in this tutoriel two texts excerpt from the [PubMed 200k RCT](https://github.com/Franck-Dernoncourt/pubmed-rct), which are used for sequential sentence classification. 
#### This dataset consists of approximately 200,000 medical abstracts. We used Word2Vec embedding of the [genism library](https://pypi.org/project/gensim/), and we used [NLTK](https://www.nltk.org/) word_tokenize.
#### We applied the CBOW (Continuous Bag of words) algorithm, and Skip-grams algorithm for the two cases, bigrams and trigrams. 
## It is advisable to consult at first the file: Word2Vec_CBOW_PubMed.ipynb.

#### We defined a context window of 5 (default value). In addition,  the minimum number of words to consider when training the model is 1.
#### Knowing that for the pre-processing of both texts, we have transformed the text into minscule, without making any other modifications.
#### We used the thee aproachs for one two and three dimensions.
#### We gave the vector representation of similar words of the word 'pain'., for the case of the CBOW algorithm.

## For more information:
#### https://datascientest.com/nlp-word-embedding-word2vec
#### http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/





