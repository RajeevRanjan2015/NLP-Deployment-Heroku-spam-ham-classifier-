# Spam-Classifier [NLP]

Classification of spam and ham by BagOfWord and TF-IDF model
### working model:
https://rajeevranjanai.herokuapp.com/

## Aim:

To create a spam classifier model and study the accuracy by using two different models such as BagOfWord Model and TF-IDF model. Does TF-IDF model improving the BagOfWord model accuracy or not?

## Data Set:

The SMS Spam is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. The dataset is tab delimited whose 1st column is Label saying spam or ham and 2nd column is sms tect. 

## Statistics about data set:

The SMS Spam Collection has a total of 4,827 SMS legitimate messages (86.6%) and a total of 747 (13.4%) spam messages.

## Approach taken:

I have use Lemmentazation process because stemming sometime not perform well as there will be meaningless takens created which can be some time confusing for user to understand and so for the machines as well.

BOW model: Frquency of document/Total Number of documents

TF-IDF: TF= Term Frequency, IDF=Inverse Document Frequency
        TF-IDF=TF*IDF 


## Result:

The accuracy achieved by Bag of Word model:  98.21  %
The accuracy achieved by TF-IDF:  97.67  %
