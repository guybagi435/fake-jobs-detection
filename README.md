# Fake jobs detection

## Description
Rnn based model for detecting fake job posts.
the model itself consist of one embedded layer,followed by an lstm layer and a dense layer(output layer) who's output represent the propability of a jobpost being fake.
## NLP
I used Glove algorithm for the purpose of vectorizing the text after it got cleaned(removing stopwords as well as lemmatizing all the words in the dataset).

## Data
the data was taken from kaggle.
i uploded the data in a compressed form inside the zip file because of maximum file size restriction.
you can find the original dataset in [here](https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction).
