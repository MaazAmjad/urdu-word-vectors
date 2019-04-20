# Urdu Word Vector Models 

Following vector models are available as of now.

## Word2Vec 

### Web News Dataset (linguistic variation 1)
----------------------------------------------------
We trained this on huge News dataset. The model knows 64653 different Urdu words.

**Linguistic Preprocessing:** Split into sentences, Word tokenization

**Parameters:** {"alpha": 0.05, "hs": 0, "iter": 15, "min_count": 50, "negative": 20, "sample": 0.0001, "sg": 1, "size": 300, "window": 5}

**Model Performance:**

- Google Analogy: **48%**

[Download](https://sgp1.digitaloceanspaces.com/urduhack/models/word-vectors/urdu_web_news_vector300_word2vec_linguistic_variation_1.bin) (**78 MB**)

### Web News Dataset (linguistic variation 2)
----------------------------------------------------
We trained this on huge News dataset. The model knows 64315 different Urdu words.

**Linguistic Preprocessing:** Split into sentences, Word tokenization, Stop word removed

**Parameters:** {"alpha": 0.05, "hs": 0, "iter": 15, "min_count": 50, "negative": 20, "sample": 0.0001, "sg": 1, "size": 300, "window": 5}

**Model Performance:**

- Google Analogy: **52%**

[Download](https://sgp1.digitaloceanspaces.com/urduhack/models/word-vectors/urdu_web_news_vector300_word2vec_linguistic_variation_2.bin) (**70 MB**)

### Wikipedia Dataset (linguistic variation 1)
----------------------------------------------------
We trained this model on whole wikipedia dataset. The model knows 17794 different Urdu words.

**Linguistic Preprocessing:** Split into sentences, Word tokenization

**Parameters:** {"alpha": 0.05, "hs": 0, "iter": 15, "min_count": 50, "negative": 20, "sample": 0.0001, "sg": 1, "size": 300, "window": 10}

**Model Performance:**

- Google Analogy: **62%**

[Download](https://sgp1.digitaloceanspaces.com/urduhack/models/word-vectors/urdu_wikipedia_vector300_word2vec_linguistic_variation_1.bin) (**21 MB**)

### Wikipedia Dataset (linguistic variation 2)
----------------------------------------------------
We trained this model on whole wikipedia dataset. The model knows 17465 different Urdu words.

**Linguistic Preprocessing:** Split into sentences, Word tokenization, Stop word removed

**Parameters:** {"alpha": 0.05, "hs": 0, "iter": 15, "min_count": 50, "negative": 20, "sample": 0.0001, "sg": 1, "size": 300, "window": 10} 

**Model Performance:**

- Google Analogy: **62%**

[Download](https://sgp1.digitaloceanspaces.com/urduhack/models/word-vectors/urdu_wikipedia_vector300_word2vec_linguistic_variation_2.bin) (**21 MB**)


## Fasttext

### Web News Dataset (linguistic variation 1)
----------------------------------------------------
We trained this on huge News dataset.

**Linguistic Preprocessing:** Split into sentences, Word tokenization

**Parameters:** {"alpha": 0.05, "hs": 0, "iter": 15, "max_n": 5, "min_count": 50, "min_n": 2, "negative": 20, "sample": 0.0001, "sg": 1, "size": 300, "window": 5, "word_ngrams": 1}

**Model Performance:**

- Google Analogy: **44%**

[Download](https://sgp1.digitaloceanspaces.com/urduhack/models/word-vectors/urdu_web_news_vector300_fasttext_linguistic_variation_1.zip) (**437 MB**)

### Web News Dataset (linguistic variation 2)
----------------------------------------------------
We trained this on huge News dataset.

**Linguistic Preprocessing:** Split into sentences, Word tokenization, Stop word removed

**Parameters:** {"alpha": 0.05, "hs": 0, "iter": 15, "max_n": 5, "min_count": 50, "min_n": 2, "negative": 20, "sample": 0.0001, "sg": 1, "size": 300, "window": 5, "word_ngrams": 1}

**Model Performance:**

- Google Analogy: **50%**

[Download](https://sgp1.digitaloceanspaces.com/urduhack/models/word-vectors/urdu_web_news_vector300_fasttext_linguistic_variation_2.zip) (**436 MB**)

### Wikipedia Dataset (linguistic variation 1)
----------------------------------------------------
We trained this model on whole wikipedia dataset.

**Linguistic Preprocessing:** Split into sentences, Word tokenization

**Parameters:** {"alpha": 0.05, "hs": 0, "iter": 15, "max_n": 5, "min_count": 50, "min_n": 2, "negative": 20, "sample": 0.0001, "sg": 1, "size": 300, "window": 10, "word_ngrams": 1}

**Model Performance:**

- Google Analogy: **59%**

[Download](https://sgp1.digitaloceanspaces.com/urduhack/models/word-vectors/urdu_wikipedia_vector300_fasttext_linguistic_variation_1.zip) (**166 MB**)

### Wikipedia Dataset (linguistic variation 2)
----------------------------------------------------
We trained this model on whole wikipedia dataset.

**Linguistic Preprocessing:** Split into sentences, Word tokenization, Stop word removed

**Parameters:** {"alpha": 0.05, "hs": 0, "iter": 15, "max_n": 5, "min_count": 50, "min_n": 2, "negative": 20, "sample": 0.0001, "sg": 1, "size": 300, "window": 10, "word_ngrams": 1} 

**Model Performance:**

- Google Analogy: **58%**

[Download](https://sgp1.digitaloceanspaces.com/urduhack/models/word-vectors/urdu_wikipedia_vector300_fasttext_linguistic_variation_2.zip) (**163 MB**)

