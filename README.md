## **Module 3 Twist -  Twitter vs Online News Tabloids**

In this project we compare the twitter discussions against the online news media sites. Due to complexity and size of the GKG dataset, we are restricting this project to Kenya and a timeframe of one week.  The data from twitter is acquired using the Twitter API where as the data from the online news media is extracted from GDELT GKG database. The NLP tasks performed on the data is topic modelling and sentiment analysis. 

The GKG Data has precomputed tone which we use to extract the sentiment and polarity scores. The themes of the articles are classified in broad categories and difficult to understand what they are all about. The headlines of the extracted articles are used to compute the specific topic which are then compared with the topics from the twitter data.

![Data_Extraction](https://github.com/denniesbor/Module_3_Twist/raw/assets/image.png)

# Code and Data
 * [Twitter Data Notebook](https://github.com/denniesbor/Module_3_Twist/blob/main/TwitterData.ipynb)
 * [GDELT Notebook](https://github.com/denniesbor/Module_3_Twist/blob/main/Knowledge_Graph_Queries.ipynb)

## Technologies
* [Python 3.8](https://www.python.org/downloads/release/python-380/)
* [spaCY](https://spacy.io/)
* [NLTK](https://www.nltk.org/)
* [Gensim](https://radimrehurek.com/gensim/)
* [Scikit learn](https://scikit-learn.org/)
* [Colab](https://colab.research.google.com/)
