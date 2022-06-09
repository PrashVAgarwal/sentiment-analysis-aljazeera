
# Sentiment Analysis using news articles from Aljazeera's website

How to Run - pip install the requirements.txt file and then run the code

In this project I try to analyze the sentiment of the news articles published on the url "https://www.aljazeera.com/where/mozambique/".
This means I try to classify the articles as positive or negative by running the content of the news articles through a sentiment analysis library.

I use the 10 most recent news articles published on the aforementioned website for this purpose. 

Data Preprocessing - I use the nltk (Natural Language Toolkit) python package to filter the Stop words i.e., those words which do not add much value/meaning to the text and so can be ignored.
I also use the tokenize package from the nltk library to tokenize the words in the text.

Beautiful soup is used to scrap the articles from the news website.

Progress Display - I use the tqdm package to display the progress of the code while it is running. This gives us visual progress bar to keep track of the code progress.

I use the TextBlob python library to do the sentiment analysis on our Preprocessed data. It gives us a polarity score which tells us how positive or negative the content of the text is. It also gives us a subjectivity score for the polarity generated.

I use the plotly library to show a graphical representation of the polarity and subjectivity generated of the scrapped news titles.

