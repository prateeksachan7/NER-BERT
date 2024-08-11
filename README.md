# NER-using-BERT

## Problem statement
NER is a task in NLP that involves finding and extracting entities—meaningful information—from sentences or other material. A word or even a group of words that all refer to the same category can be considered an entity. The goal of this project is a system itself understands the meaning of a given word. e.g. "My name is Aditya." In this sentence name - Aditya singnifies a 'person'. 

## Solution proposed
BERT frequently emerges as a machine learning model whose performance we may rely on when it comes to tackling NLP issues. Its ability to learn information from a word sequence in both directions plus the fact that it has been pre-trained on more than 2,500M words make it a strong model to deploy. The first step of a NER task is to detect an entity. To make sure that our BERT model knows that an entity can be a single word or a group of words, then we need to provide information about the beginning and the ending of an entity on our training data via the so-called Inside-Outside-Beginning (IOB) tagging. After detecting an entity, the next step in a NER task is to categorize the detected entity.

## Dataset used
The dataset which has been used in this project is CoNLL-2003, which is specifically used for NER task.

## Tech stack used
1. Python 3.8
2. FastAPI
3. Deep learning
4. Natural language processing
5. BERT
6. Docker

## Infrastructure required
1. Google compute engine
2. Google cloud storage
3. Google artifact registry
4. Circle CI


## `ner` is the main package folder which contains -

**Components** : Contains all components of this Project
- DataIngestion
- DataTransformation
- ModelTrainerAndEval
- ModelEvaluation
- ModelPusher

**Custom Logger and Exceptions** are used in the Project for better debugging purposes.

## Conclusion
The most significant task in NLP is NER tagging. NER is used in a variety of ways. From a given text, NER can be used to extract important information.
