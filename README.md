# Twitter Text Classification

In this project, I tested the BERT and GloVe models to classify tweets into one of two topics (disaster or non-disaster). The datasets used in this project can be found at: https://www.kaggle.com/c/nlp-getting-started/data

Initially, I created a model using the **GloVe** embeddings and achieved F1 score of **0.74**. This can be found in [twitter_text_classification_GloVe.ipynb](https://github.com/kumarsoma/twitter_text_classification/blob/master/twitter_text_classification_GloVe.ipynb). 

I then created a separate model by implementing **BERT** and achieved F1 score of **0.79**. This can be found in [twitter_text_classification_BERT.ipynb](https://github.com/kumarsoma/twitter_text_classification/blob/master/twitter_text_classification_BERT.ipynb).

The [clean_json.txt](https://github.com/kumarsoma/twitter_text_classification/blob/master/clean_json.txt) contains pairs of incorrect and correct words. Incorrect words in tweets include contractions, abbreviations, typos, and special characters, and they will be replaced by the corresponding correct words. This file was read in the *clean* function of the .ipynb files above.

