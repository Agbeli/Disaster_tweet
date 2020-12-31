# Disaster_tweet
Disaster tweet classification 

- The goal of this project is classify tweets that contains some level of fake or real about disaster events.
- This is an NLP problem for a given text one has to categorize the text as be **fake or real** about disaster incident. 
    - For my solution I had to understand the nature of the texts by performing exploratory analysis. After perform some data cleaning. 
    - Preprocess the texts by performing standard tasks for text such as tokenization, normalization, stemming and removing of stopwords from the texts. 

### Modeling phase:

- At the initial I considered baseline model by using naive bayes model on the train and test dataset. 
- To improve the model, I further consider one of the transformers models know as **BERT** which is pretrained model. I had to fine-tuned the model to solve my  problem. 
- The transformers models are known to be state of the art models for most NLP tasks. From the notebook, I had implemented cross-validation techniques to ascertain a more 
robust model for generalization. I had an accuracy of 97% wnen I implemented the bert model. [NOTEBOOK](Disaster_tweet_classification.ipynb) 

- I had to trained this using google colab in order to have access to gpu. 
