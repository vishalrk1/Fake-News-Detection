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
- Build an model with title text data using huggingfaces distillbert model

# Results

<img src="Images/Models Result.png" width=70% height=70%>

## Accuracy plot
<img src="Images/Accuracy Plot.png" width=70% height=70%>

## F-1 Score plot
<img src="Images/F1-Score Plot.png" width=70% height=70%>

## Packages Used
- Tensorflow
- tensorflow_text
- tensorflow_hub
- transfromers
- sklearn
- Matplotlib
- numpy
- pandas

## Contact Me

<p align="start">
    <a href="https://github.com/vishalrk1" target="_blank">
        <img alt="Github" src="https://img.shields.io/badge/Github-%23F37626.svg?style=for-the-badge&logo=github&logoColor=white" />&nbsp;
    </a>
<!--     <a href="https://twitter.com/ArizArmeidi" target="_blank">
        <img src="https://img.shields.io/badge/-Twitter-2CA5E0?logo=twitter&style=for-the-badge&logoColor=white&color=black" alt="Twitter" />
    </a> -->
    <a href="https://www.linkedin.com/in/vishal-karangale-126492216/" target="_blank">
        <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-%23F37626.svg?style=for-the-badge&logo=linkedin&logoColor=white" />&nbsp;
    </a>
     <a href="https://www.instagram.com/vishal_rk1/" target="_blank">
       <img alt="Instagram" src="https://img.shields.io/badge/Instagram-%23F37626.svg?style=for-the-badge&logo=instagram&logoColor=white" />&nbsp;
    </a>
</p>

