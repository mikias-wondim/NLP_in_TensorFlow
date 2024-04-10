# NLP_in_TensorFlow
# Introduction to NLP Fundamentals

**Natural Language Processing (NLP)** is a subfield of artificial intelligence that gives computers the ability to understand and generate human language. NLP is used in a wide range of applications, including:

* Text Classification
* Machine translation: Translating text from one language to another.
* Text summarization: Creating concise summaries of longer texts.
* Sentiment analysis: Determining the sentiment of a text (e.g., positive, negative, or neutral).
* Named entity recognition: Identifying named entities in a text (e.g., people, places, organizations).
* Question answering: Answering questions based on a text or a set of texts.


NLP is a complex and challenging field, but it is also a rapidly growing one. As the amount of text data available 


## NLP Text Classification

The first notebook name `Introduction_to_NLP_in_TensorFlow.ipynb` is a  **Text Classification NLP using Kaggle's Disaster Tweets Dataset**

### Objective:
We will use NLP techniques to classify tweets as either related to a disaster or not. We will use the NLP with Disaster Tweets dataset from Kaggle.

### Dataset:
The NLP with Disaster Tweets dataset contains over 10,000 tweets labeled as either related to a disaster or not. The dataset is divided into training and test sets.


## SkimLit 📄🔥

The second project focuses on replicating the deep learning model behind the 2017 paper "PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts." The paper introduced the PubMed 200k RCT dataset, which consists of approximately 200,000 labeled Randomized Controlled Trial (RCT) abstracts. The goal of the dataset is to explore the ability of Natural Language Processing (NLP) models to classify sentences within abstracts based on their sequential roles.

### Problem Statement
With the increasing number of RCT papers being released, those without structured abstracts can be challenging to read, which can slow down researchers moving through the literature. The solution proposed in this project is to create an NLP model that can classify abstract sentences into their respective roles (e.g., objective, methods, results, conclusions). This model enables researchers to skim through the literature quickly and dive deeper into specific sections when necessary.

### Objectives
- **Dataset Preparation:** Download the PubMed RCT200k dataset from GitHub and preprocess the data for modeling.
- **Modeling Experiments:** Conduct a series of modeling experiments to build the NLP model, including:
  - Baseline model using TF-IDF classifier.
  - Deep models with different combinations of token embeddings, character embeddings, pretrained embeddings, and positional embeddings.
  - Building a multimodal model that takes multiple types of data inputs.
  - Replicating the model architecture from the referenced paper.
- **Analysis and Evaluation:** Evaluate model performance, identify the most wrong predictions, and make predictions on PubMed abstracts from real-world data.

Happy learning and experimenting! 🚀📚
