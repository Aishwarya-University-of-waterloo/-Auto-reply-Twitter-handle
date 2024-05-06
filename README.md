The goal of this Twitter Support project is to listen to live tweets with needed tags and publish them to a Kafka topic, which will then be ingested by Spark Stream and fed through an NLP pipeline for further processing and reacting. The tweets will then be classified using machine learning models like LSTM based on sentiment and query category before being responded to with a custom selected ID using Flask and the tweepy API.

Tech Stack:

➔ Language: Python3
➔ Services: Confluent Kafka, Spark
➔ Libraries: tweepy, Flask, kafka, spacy, sklearn, keras, numpy, pyspark, nltk, matplotlib, os

1. Tweepy is a Twitter client that allows you to read and respond to tweets.
2. Flask is used to set up an API for a response.
3. Data ingestion with Kafka.
4. Sklearn is a tool for evaluating and encoding models.
5. For preprocessing, use Nltk.
6. Spacy is a tool for recognising named entities.
7. Pandas is a programming language that may be used to manipulate and analyse data.
8. Matplotlib is a graph charting library.
9. Numpy is a Python library for array and math operations.
10. Tensorflow and Keras are used to load and construct models and embeddings.
11. Pyspark is a Python library for creating UDFs and streaming data.
12. Operating system for folders.
