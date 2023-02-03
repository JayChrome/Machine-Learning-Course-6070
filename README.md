# Machine-Learning-Course-6070
This repository hosts code dedicated to my eperience in ML 6070. The files need to be run in Python and are sourced from my Machine Learning class. Download the notebooks, open them on you preferred python program and then run all the code to see the outputs. I am currenly useing Jupyter Lab Notebook 3.3.2. Runtime should be about 4 seconds for the entire file, unless otherwise noted.

<b>CA01</b> - is exemplary of an exploraty data analysis (EDA) for House Price Dataset. All steps of EDA are included besides collinearity, dimensionality reduction, and handle class imbalance. 

<b>CA02</b> - This partuclar code is focused on creating an email spam filter for 702 emails and measuring the accuracy of the model with two datasets, train-mails and test-mails, through Naive Bayes. The emails are already split between spam and non-spam messages and the model was tested with a 70/30 split for training and test data. This code takes approximately 80 seconds to run on python lab and yeilds an accuracy score of 1.0. Meaning that the model correctly predicted classiicaions 100% of the time. 

The training, test, and emails are locaed in the file data.zip, within my repository for reference. 

<b>The libraries and source for the data are below:</b>

<br>In this section we are importing libraries
<br>The OS module in Python provides functions for creating and removing a directory (folder), fetching its contents, changing and identifying the current directory
<br>Import numpy allows us to turn our dataframe into an array
<br>Counter is an unordered collection where elements are stored as Dict keys and their count as dict value. 
<br>Sklearn naive bayes and metrics will help us run the model and get an accuracy score
<br>Import time allows us to work with time
<br>from subprocess import check_output gets the output of the calling program in python.

<br>import os
<br>import numpy as np
<br>from collections import Counter
<br>from sklearn.naive_bayes import GaussianNB
<br>from sklearn.metrics import accuracy_score
<br>import time
<br>from subprocess import check_output

