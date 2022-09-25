# Projects On NLP

## Text Classification on the Newsgroup dataset
This dataset is a collection newsgroup documents. The 20 newsgroups collection has become a popular data set for experiments in text applications of machine learning techniques, such as text classification and text clustering.

The dataset can be taken from [kaggle](https://www.kaggle.com/datasets/crawford/20-newsgroups)

## Technology Stack Used:

### Library 
1. **TorchVision** <br>
2. **Numpy** <br>
3. **Pandas** <br>
4. **MatplotLib**<br>
5. **Regular Expressions**<br>
### Frameworks 

1. **PyTorch**

## Working 

1. We have preprocessed the dataset to create features.
2. We have considered word length of more than 3 using regex functions after removing stop words to create instances.
3. We have used Multinomial Naive Bayes from Scikit Learn to classify between different classgroups achieving an accuracy of 89%. 
4. We have developed Naive Bayes from scratch and compared the accuracy with the sklearn's Naive bayes.
