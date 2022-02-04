# Predicting DogeCoin Price Bubbles using Epidemic Modeling

For CSE-8803 : Data Science for Epidemiology by Dr. B. Aditya Prakash, Fall 2021

Steps for runnning the notebooks - 

Create a Conda Environment:
>> conda env create --name "dogeepi" <br>
>> conda install pandas <br>
>> conda install numpy <br>
>> pip install hmmlearn<br>
>> pip install twint<br>
>> conda install scikit-learn<br>
>> conda install jupyter<br>
>> conda install matplotlib<br>

After that type the command: jupyter notebook 

It will open the directory, then open the following notebooks and run each cell line by line. 

Twitter Sentiment Analysis:

1. Tweets are collected using python's TWINT library which allows us for ftching raw tweets with keywords in the set ["doge", "#doge", etc.]
2. The duplicates are removed and tweets are cleaned to perform lemmatization and tokenization of the tweets. 
3. Finally after removing the unwanted symbols, sentiment analysis is performed for the tweets to be assigned a score based on the NLTK library. 

ILI Notebook - 
1. Train HMM on influenza data
2. Train HMM on Social media data
3. Train HMM on doge coin
4. Predict doge coin prices using social media data 
5. Train and predict the covid data and influenza data using HMM 
