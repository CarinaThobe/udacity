# All i used is documented in my code capstone.ipynb (or: capstone_code.html which is the html export of the ipython notebook)

# I imported the following libraries:
import numpy as np
import pandas as pd
from IPython.display import display 
%matplotlib inline
import matplotlib.pyplot as plt 
from sklearn.preprocessing import StandardScaler, MinMaxScaler
from sklearn.cross_validation import train_test_split
from imblearn.under_sampling import RandomUnderSampler
from imblearn.over_sampling import SMOTE
from sklearn import metrics
from sklearn.linear_model import LogisticRegression
from sklearn.svm import SVC
from sklearn import tree
from sklearn.ensemble import RandomForestClassifier

# The Dataset is downloadable from kaggle: 
https://www.kaggle.com/dalpozz/creditcardfraud 
