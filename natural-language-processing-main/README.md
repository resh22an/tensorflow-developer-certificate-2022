# NLP

- This repo contains preparation material for [TensorFlow Developer Certification](https://www.tensorflow.org/certificate) (Content as in Coursera's [DeepLearning.AI TensorFlow Developer](https://coursera.org/professional-certificates/tensorflow-in-practice) course)
- The below projects use ```tf.keras.layers.TextVectorization```instead of the deprecated ```tf.keras.preprocessing.text.Tokenizer```

## Text Classification

- *IMDB Reviews dataset* - Building a sentiment classification model to distinguish between positive and negative movie reviews
  - [IMDB Reviews - DNN](https://github.com/resh22an/natural-language-processing/blob/f35b115b30e7366d1284387825f5155b726992f4/text-classification/IMDBReviews_DNN.ipynb)
  - [IMDB Reviews - RNN, CNN](https://github.com/resh22an/natural-language-processing/blob/f35b115b30e7366d1284387825f5155b726992f4/text-classification/IMDBReviews_RNN_CNN.ipynb)
- [Sentiment140 dataset](https://github.com/resh22an/natural-language-processing/blob/a72121a89aebec190151d0c11f56ea98e361f0e3/text-classification/Sentiment140-mini.ipynb) - Classify tweets based on their positive or negative sentiment using [GloVe embeddings](https://nlp.stanford.edu/projects/glove/)
- [BBC News Archive](https://github.com/resh22an/natural-language-processing/blob/c7729b71c5a1185134d5f52f49e18e3b17393357/text-classification/BBCNewsArchive.ipynb) - Classify previously unseen news articles into the right category by training it on *BBC News Classification dataset*
- *News Headlines Dataset for Sarcasm Detection* - Build a classifier to determine whether the news headlines are sarcastic or not
  - [Sarcasm - DNN](https://github.com/resh22an/natural-language-processing/blob/f35b115b30e7366d1284387825f5155b726992f4/text-classification/Sarcasm_DNN.ipynb)
  - [Sarcasm - RNN, CNN](https://github.com/resh22an/natural-language-processing/blob/f35b115b30e7366d1284387825f5155b726992f4/text-classification/Sarcasm_RNN_CNN.ipynb)


## Text Generation

- [Sonnet generation](https://github.com/resh22an/natural-language-processing/blob/dcf37384946a9572053dd219329c2955b21c16e1/text-generation/ShakespeareSonnets.ipynb) - Predict the next word in a text sequence by training the model using a corpus of *Shakespeare's sonnets*
- *Song generation* - Build a model to generate a new song by training it on the existing lyrics
  - [Training on a single song](https://github.com/resh22an/natural-language-processing/blob/dcf37384946a9572053dd219329c2955b21c16e1/text-generation/IrishSong.ipynb) 
  - [Training on lyrics dataset](https://github.com/resh22an/natural-language-processing/blob/dcf37384946a9572053dd219329c2955b21c16e1/text-generation/IrishPoetry.ipynb)
