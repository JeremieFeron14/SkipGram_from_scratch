# SkipGram_from_scratch


Implementation of skipgram with negative sampling for scratch for the NLP course at CentraleSupélec (2021). 

Based on:

Initial word2vec paper: (Efficient Estimation of Word Representations in Vector Space, 2013)
Fasttext paper: (Enriching Word Vectors with Subword Information, 2017)

Usage:
```
python3 skipgram --text <PATH_TO_FILE>
```

Additional options:

 --mode_OOV <bool>: default False, True if you want the representations to be learned from n-grams rather than words. Gives etter results when predicting out of vocabulary words at test time (Enriching Word Vectors with Subword Information, 2017).
 
 if testing trained model:
 --test
 --model <PATH_TO_MODEL>  
