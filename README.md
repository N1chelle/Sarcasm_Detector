# Sarcasm Detector

### The Goal

The project is aimed to build a neural network model to identify sarcasm in textual data.

### About the Dataset

Dataset from [Kaggle](https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection) has been used for this project.
This News Headlines dataset for Sarcasm Detection is collected from two news websites. [*TheOnion*](https://www.theonion.com/) aims at producing sarcastic versions of current events and the [authors](https://rishabhmisra.github.io/publications/) have collected all the headlines from News in Brief and News in Photos categories (which are sarcastic). They collected real (and non-sarcastic) news headlines from [*HuffPost*](https://www.huffpost.com/).

Each record consists of three attributes:

* `is_sarcastic`: 1 if the record is sarcastic otherwise 0

* `headline`: the headline of the news article

* `article_link`: link to the original news article. Useful in collecting supplementary data

### Visuals

Wordcloud of NOT Sarcastics news articles:

![](https://github.com/N1chelle/Sarcasm_Detector/blob/main/Images/wordcloud1.png?raw=true)

Wordcloud of Sarcastic news articles:

![](https://github.com/N1chelle/Sarcasm_Detector/blob/main/Images/wordcloud2.png?raw=true)

Accuracy & Loss Graph:

![](https://github.com/N1chelle/Sarcasm_Detector/blob/main/Images/accuracy.png?raw=true) 
![](https://github.com/N1chelle/Sarcasm_Detector/blob/main/Images/screenshot2.png?raw=true)


### Further Improvements

* I would like to further improve the code by making changes in the layers of the neural network and the epochs to get a better result.
* Also, I would like to test to see if it can distinguish between real and fake news articles.

