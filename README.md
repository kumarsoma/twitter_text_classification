Initially, I created a model using the **GloVe** embeddings and achieved F1 score of **0.74**. This can be found in the *twitter_text_classification_GloVe.ipynb* file. 

I then created a separate model by implementing **BERT** and achieved F1 score of **0.79**. This can be found in the *twitter_text_classification_BERT.ipynb* file

The *clean_json.txt* contains pairs of incorrect and correct words. Incorrect words in tweets include contractions, abbreviations, typos, and special characters, and they will be replaced by the corresponding correct words. This file was read in the *clean* function of the .ipynb files above.