# dostoevsky-writer
A neural network that can generate a bit of Dostoevsky-like text using LSTM layers and GloVE word embeddings

## Inputs
I took Project Gutenberg's *Crime and Punishment* pdf and did a bit of manual cleaning to get rid of metadata.
In addition, I used the 100 dimensional GloVE word embeddings found [here](https://nlp.stanford.edu/pubs/glove.pdf "Link to GloVE's download page"). I did not uploade these word embeddings, as even the 100 dimensional word embeddings are 338MB.

## The Model
I used an N-gram approach that I learned in a Coursera course entitled "Natural Language Processing in Tensorflow." This approach was detailed in [this](https://github.com/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/NLP_Week4_Exercise_Shakespeare_Answer.ipynb) GitHub IPython Notebook.

## The Results
are pretty bad. Text generation is a difficult task, and I am relatively new to NLP. The text may "sound" like Dostoevsky, but there is little real meaning to it. 