# Pre-trained Urdu word2vec models 


## Web News Dataset (linguistic variation 1)

We trained this on huge News dataset. The model knows 64653 different Urdu words.

**Linguistic Preprocessing**: Split into sentences, Word tokenization

**Parameters**: {"alpha": 0.05, "hs": 0, "iter": 15, "min_count": 50, "negative": 20, "sample": 0.0001, "sg": 1, "size": 300, "window": 5}

#### Model Performance:

- Google Analogy: **48%**

[Download](https://sgp1.digitaloceanspaces.com/urduhack/models/word-vectors/urdu_web_news_vector300_word2vec_linguistic_variation_1.bin) (*78 Mbytes*)
