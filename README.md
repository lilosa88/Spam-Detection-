# Spam-Detection-

# Objective

Dataset is obtained from [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). The SMS Spam Collection is a public set of SMS labeled messages that have been collected for mobile phone spam research. The objective is to build a predictive model that predicts if a message is spam or not. 

# Code and Resources Used

- **Phyton Version:** 3.0
- **Packages:** pandas, numpy, sklearn, re, nltk

# Data description

The collection is composed by just one text file, where each line has the correct class followed by the raw message. We offer some examples bellow:

ham What you doing?how are you?
ham Ok lar... Joking wif u oni...
ham dun say so early hor... U c already then say...
ham MY NO. IN LUTON 0125698789 RING ME IF UR AROUND! H*
ham Siva is in hostel aha:-.
ham Cos i was out shopping wif darren jus now n i called him 2 ask wat present he wan lor. Then he started guessing who i was wif n he finally guessed darren lor.
spam FreeMsg: Txt: CALL to No: 86888 & claim your reward of 3 hours talk time to use from your phone now! ubscribe6GBP/ mnth inc 3hrs 16 stop?txtStop
spam Sunshine Quiz! Win a super Sony DVD recorder if you canname the capital of Australia? Text MQUIZ to 82277. B
spam URGENT! Your Mobile No 07808726822 was awarded a L2,000 Bonus Caller Prize on 02/09/03! This is our 2nd attempt to contact YOU! Call 0871-872-9758 BOX95QU- 


# Preprocessing

- We clean the data by removing punctuations, stopwords and applying lowercase. Thus we use PorterStemmer, stemming is the process of reducing words to their word stem.
- We convert our sentences into vectors using Bag of words model.
- We applying encoding into the column label.
- Train and test split. 

# Machine Learning Models

- Naive Bayes Model
 
 Train Random Forest's Accuracy:  0.9887
 
 Test Random Forest's Accuracy:  0.9838
 
