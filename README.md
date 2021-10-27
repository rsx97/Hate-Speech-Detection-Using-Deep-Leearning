# Hate-Speech-Detection-Using-Deep-Leearning
The main objective of this study was to develop a language independent detection method to detect hate speech on social networks using LSTM , then at the end make an implementation with flask .


# Overview:

As online content continues to grow, so does the spread of hate speech. We identify and examine the challenges faced by automated methods to detect hate speech in text. Among these challenges are subtleties of language, different definitions of what constitutes hate speech, and limitations on the availability of data for training and testing these systems. Additionally, many newer methods have interpretability issues, which means they may have difficulty understanding why the system makes the decisions they make. We propose an approach using the "Recurrent Neural Network" which achieves performances close to the state of the art, while being simpler and easier to produce interpretable decisions than other neural methods or else. Machine Learning approach. We also discussed the technical and practical challenges that still exist for this task.

The entire process involves the following:

1.  New tweet received
2.  A volunteer takes the tweet
3.  Does hate check for the  tweet
4.  Determines if the tweet is Hate or not.

# The problem:

1.  Dataset for hate speech are not available
2.  Each tweet takes too much time for hate checking 
3.  Number of volunteers is very small
4.  Classifying hate speech can be tough : -https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0221152

Read the above article to understand different types of fake news

# Our Solution:

Our machine learning model is made to help the hate checkers and not replace them. It reduces the time to to check articles by giving insights to the hate checker as to what level of scrutiny it should use for the particular article.


# Working:

## Dataset used :
https://github.com/rsx97/HateSpeechDataset

## Method used :
LSTM
https://colah.github.io/posts/2015-08-Understanding-LSTMs/

Final Result:

From the frontend app  you can enter any type of input : there is 7 methods of cleaning (numbers,urls,emojis.....)

## How it works :
Firstly you should create virtualenvironment for your flask project in yor desktop.

    install virtualenvironment : install virtualenvironment at your terminal or dos

    pip install virtualenv

    Clone the repository and access it with Windows PowerShell

    virtualenv venv : created virtualenvironment named "venv"

and activate your venv.
Now, you can start install flask.
-pip install Flask
-Run the Windows PowerShell
-Type in the command line : flask run

## DEMO Image:
<img src="https://github.com/rsx97/Hate-Speech-Detection-Using-Deep-Leearning/blob/main/Hate%20Speech%20-%20with%20Pre%20process/static/image/hateSpeechUI.png" width=800/>
