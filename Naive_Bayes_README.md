## Name of project
Spam eMail Detection using Naive Bayes Classification Algorithm

## Project Overview 
This project is given a dataset of eamils and purpose of this project is to create a dictionary having most common 3000 words and form a frequency matrix for each email.
The dataset contains 702 emails, both spam and non spam emails, using test mails to predict mails need train.

## Instruction
Please use the data from google drive (link in the bottom) to run the code 

## Installation instructions
Use the following packages:

```bash
os
numpy
collections
sklearn.naive_bayes
sklearn.metrics
```
## Usage 
```python
import os
import numpy as np
from collections import Counter
from sklearn.naive_bayes import GaussianNB #use Gaussian model
from sklearn.metrics import accuracy_score
from google.colab import drive #read file from google drive
```

## Operating instructions
1. First step is to improt all packages that will use later and mounted in order to read files from drive.
2. Next step is clean up the data, this part create a dictionary with the most common 3000 words will use in the email.
3. Next part is feature extraction. After define spam message, it will output frequency matrix for each email as a list. 
4. Import data from drive and use Gaussian model to predict and gives the accuracy score. 

## Conclusion
Using Gaussian model training gives 96% of accuracy which is a very good prediction and Gaussian model follows normal distribution.

## Colab access
https://drive.google.com/file/d/1W6qTMbpQWkWJxTDQuMrRaske1dETQrk7/view?usp=sharing

## Data
https://drive.google.com/drive/folders/1xjBHo0DrR8aHTUnv5JyP6vxo7yFBe_3l?usp=sharing


## Contact information
Name: Ziyao Cui
