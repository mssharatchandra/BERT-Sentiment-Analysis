# BERT-Sentiment-Analysis
## What is BERT?
BERT, short for Bidirectional Encoder Representations from Transformers, is a Machine Learning (ML) model for natural language processing. It was developed in 2018 by researchers at Google AI Language and serves as a swiss army knife solution to 11+ of the most common language tasks, such as sentiment analysis and named entity recognition.

Language has historically been difficult for computers to ‘understand’. Sure, computers can collect, store, and read text inputs but they lack basic language context.

So, along came Natural Language Processing (NLP): the field of artificial intelligence aiming for computers to read, analyze, interpret and derive meaning from text and spoken words. This practice combines linguistics, statistics, and Machine Learning to assist computers in ‘understanding’ human language.

Individual NLP tasks have traditionally been solved by individual models created for each specific task. That is, until— BERT!

BERT revolutionized the NLP space by solving for 11+ of the most common NLP tasks (and better than previous models) making it the jack of all NLP trades.

## BERT model size & architecture
Let’s break down the architecture for the two original BERT models:<br>
![image](https://user-images.githubusercontent.com/74253329/184485865-1614ed30-2dd0-4ca8-a82f-afac97a62024.png) <br>
Here’s how many of the above ML architecture parts BERTbase and BERTlarge has:<br>
![image](https://user-images.githubusercontent.com/74253329/184486123-ddffacd5-69f2-4442-af4c-70f620ca3f79.png)<br>

## Building BERT Pipeline
In our project we do the following:
* Define and run a pipeline using a directed acyclic graph (DAG) with specific pipeline parameters and model hyper-parameters
* Define a processing step that cleans, balances, transforms, and splits our dataset into train, validation, and test dataset
* Define a training step that trains a model using the train and validation datasets
* Define a processing step that evaluates the trained model's performance on the test dataset
* Define a register model step that creates a model package from the trained model
* Define a conditional step that checks the model's performance and conditionally registers the model for deployment
