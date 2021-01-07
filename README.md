# NLP Workshop for ODSC 2017
Feel free to follow along in this notebook, or download it and run it yourself. Instructions below.

# Installation instructions

#### clone the repository

#### download pretrained google word vectors

Run `python -m gensim.downloader --download word2vec-google-news-300` or follow the instructions in the gensim documentation.

#### download pretrained char-rnn for Yelp
`curl -O https://s3.amazonaws.com/yelp-weights-files/Sep-26-all-00-0.7280.hdf5`

rename the file to 'pretrained-yelp.hdf5'
