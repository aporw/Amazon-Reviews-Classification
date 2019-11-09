# Amazon-Reviews-Classification
Classifying product good/bad based on customer reviews

Input : Reviews in the form on text 
Output : Product is good or bad

# Machine Learning Methods:

Create vectorizer (count, set, tf-idf) and use words as features 

# Deep Learning Methods:

Create vocabulary and index of words , padd the index , define an initial embedding with fix dimension and train data. 

Best Model: LSTM

# Manual Testing on Raw Data:

# Input:
'I am in love with this product. I mean it fits my needs perfectly. So glad'

Output:
positive prob:  0.998 ,negative prob   0.002

# Input:
'I hate this one, so bad , i cant believe all was lie'

positive prob:  0.013 ,negative prob   0.987

# Input: 
'I did not like it much, but it was not so bad'

positive prob:  0.23 ,negative prob   0.77


# Input:
'Somethings are good but few are average as well, i will it is say ok buy'

positive prob:  0.33 ,negative prob   0.67

