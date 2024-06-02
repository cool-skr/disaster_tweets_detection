## Disaster Tweet Classification
#### Overview
In today's age of social media, real-time information dissemination is crucial, especially during disasters and emergencies. Twitter, being one of the most widely used platforms, becomes a valuable source of information during such events. However, not all tweets pertaining to disasters are easily identifiable, making it challenging to filter relevant information efficiently. This project addresses this challenge by developing a machine learning model to automatically classify disaster-related tweets.

#### Dataset
The dataset used for this project is the [Disaster Tweets Dataset](https://www.kaggle.com/competitions/nlp-disaster-tweets) from Kaggle. It consists of thousands of tweets labeled as either disaster or non-disaster. The dataset is split into training and testing sets to train and evaluate the model's performance.

#### Preprocessing
Pre - processed the text for removing unnecessary components of the text,
like URLs, Punctuations, Special Characters, Stopwords using NLTK
Libraries.
Used the Standard Tokenizers for each model from their corresponding
libraries from the Transformers Library.

#### Model
● BERT, Roberta, and Distilled BERT models.<br>
● Ensembled all three models using Majority Voting Principle<br>
● Fine - tuned the Distilled BERT by adding more hidden and activation layers
(ReLU and Sigmoid)<br>
● Optimized the training processes using Adam Optimizer
#### Results
The performance of the trained model on the test dataset is as follows:

Accuracy: 76.74%

We finished No 1 in the live competition.
