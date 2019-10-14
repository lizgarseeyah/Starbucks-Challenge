
__Elizabeth Garcia Project 6: Starbucks Capstone Challenge__
__Project Motivation:__
The purpose of the Starbucks Capstone Challenge is to use the 
data to identify which groups of people are most responsive to
which type of offer, and how best to present each type of offer.
Starbucks wants to understand their customer on an individual level to understand what type of
offers excite them the most. The data used in this capstone project
is simulated customer behavior on the Starbucks mobile reward app.


__Business Questions to extract from data:__
1. Identify the demographic data
2. Identify customer attributes and buying behavior

__Summary of Modules and Libraries Used:__
import pandas as pd
import numpy as np
import math
import json
from datetime import datetime
import numpy as np
import pandas as pd
import re
import os
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import LabelBinarizer, MultiLabelBinarizer
% matplotlib inline
 
 Python version 3

__File description:__
'portfolio.json'
'profile.json'
'transcript.json'
'Starbucks_Capstone_notebook'

__Summary of Results:__
In conclusion, the random forest model predicted how much someone will spend based on their demographics and offer type. The strategy for solving this problem was two-fold: the first step was to combine the portfolio, profile, and transaction data and the second step involved assessing the accuracy and F-score from the chosen model. 
 After comparing the results from each model, the random forest model had the best training data accuracy, F-score and training time. The final model trained on reduced data, based on the random forest model, had accuracy of 0.985 and an F-score of 0.986. To further improve this project, I would recommend selecting and evaluating different features such as real income.


A complete summary of the results can be viewed in the blog post.


