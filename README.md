## Project: analyzing-IMDb-data-in-Keras

### Overview
In this notebook, I have analyzed the sentiments in the IMDB movie reviews using Keras. The data has been already pre-processed, where all the words have numbers, and the reviews come in as a vector with the words that the review contains. For example, if the word 'the' is the first one in our dictionary, and a review contains the word 'the', then there is a 1 in the corresponding vector. The output comes as a vector of 1's and 0's, where 1 is a positive sentiment for the review, and 0 is negative.

### Data

The dataset comes preloaded in Keras, which means I don't need to open or read any files manually and one simple command will get us training and testing data. The command to load the data will actually split the words into training and testing sets and labels. There are 25000 movie reviews available in the dataset for analysis.
