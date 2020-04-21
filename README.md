# Sentiment-Classification


Built a Natural language processor to classify whether a review is positive or a negative one. With the movie reviews taken from IMDB, used Bi-Directional LSTM to classify the review as positive and negative. 


The Dataset of 25,000 movie reviews from IMDB, labeled by sentiment (positive/negative). Reviews have been preprocessed, and each review is encoded as a sequence of word indexes (integers). For convenience, the words are indexed by their frequency in the dataset, meaning the for that has index 1 is the most frequent word. Use the first 20 words from each review to speed up training, using a max vocab size of 10,000. As a convention, "0" does not stand for a specific word, but instead is used to encode any unknown word

