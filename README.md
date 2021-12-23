# Fake News Detection
An NLP Model to classify news articles as real or fake

# Dataset Used
**[Fake News or Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)**
- Dataset has 3 columns title, text, labels
- title : Title of news
- text : Complete News Article
- label : REAL or FAKE

# Modeling Experiments
 **Preprocessing Steps**
 - lower casing all text data
 - removing punctuations, stopword and HTML components

**All Models**

I have used only text data ( complete news article ) for all the following models
- Base Model was naive bayse model 
- Simple Dense layer Models
- model with LSTM Layer
- model with bidirectional LSTM layers
- model with Conv1D layers
- model using pretrained embeddings

