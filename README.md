Initially, I created a model using the **GloVe** embeddings and achieved F1 score of **0.74**. This can be found in the *twitter_text_classification_GloVe.ipynb* file. 

I then created a separate model by implementing **BERT** and achieved F1 score of **0.79**. This can be found in the *twitter_text_classification_BERT.ipynb* file

The *clean_json.txt* contains words with contractions, abbreviations, typos, and special characters. In the .ipynb files above, there is a *clean* function in which I read the words from the *clean_json.txt* file to correct them.