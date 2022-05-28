This repository contains three lab assignments for the Deep Learning course at Vilnius University.

# GMMFirst
This colab notebook contains a simple convolutional neural network model and it's training for classifying emotions from emotional speech.

The model is trained on AESDD dataset:
http://m3c.web.auth.gr/research/aesdd-speech-emotion-recognition/

# GMMSecond
This colab notebook contains modifying and fine-tuning a ResNet50 model for multiple tasks at once, namely classification and object detection.

The model is fine-tuned using a part of Open Images Dataset V6:
https://storage.googleapis.com/openimages/web/index.html

# GMMThird
This colab notebook contains an implementation of semantic search using cosine similarity.

It can be run by using a pretrained version of Electra, which is a question-answer oriented transformer model, or GPT-2, which is great for generating text given prompts, but here it's used for asymmetric search.

Search is also implemented two ways for comparison, first being using the FAISS tool, second being just calculating the cosine similarity for every entry in the corpus and then sorting for desired values.
https://github.com/facebookresearch/faiss

The corpus used for this notebook was 11000 reviews scraped from a single game on Steam.