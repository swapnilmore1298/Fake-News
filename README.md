# Fake-News-Detection Bot and WebApp with Flask
Project created in _Algorithm6.0 Hackathon_ at AIKTC college in 24 hours.
### Team Mates:
1. Swapnil More
2. Divya Kapil
3. Navjot Singh Rajput
4. Mahitha BSL

### Tech Stack Used:
1. NLP
2. Flask
3. TelegramBot
4. newsapi

## Dataset is as below
### News and its labels:
![alt text](https://github.com/swapnilmore1298/Fake-News/blob/master/image/Capture.PNG)

### created this dataset using Newsapi()

## Model applied
1. TF-IFD
2. Trained with PassiveAgressive Classifier

## Related news findings
### 1. Extracted keywords from news using Textblob
- Found _Noun phrases_
- Fed them to newsapi() to find related news
### 2. Also display top trending news using newsapi()

## TF-IDF explained
### TF (Tag frequency)
Here frequency of a word occurence in a document determines its importance. Higher the TF, higher the importance.
### IDF (Inverse Document Frequency)
Here frequenct of a word between the documents is calculated to find its triviality. If a words occurs frequently in all documents, them its importance is irrelevant.

_This helps us to vectorize the labels with important details while training_

