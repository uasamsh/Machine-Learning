### Installation Libraries ipynb



Steps:

Creata a new conda environment python\_ml

install the following packages:

python conda install python

pandas

numpy

matplotlib

seaborn

scipy

scikit-learn

jupyter

openpyxl

plotly

pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter openpyxl plotly



import pandas as pd

import numpy as np 

import matplotlib.pyplot as plt 


from sklearn import linear_model
reg = linear_model.LinearRegression()
reg.fit([[0, 0], [1, 1], [2, 2]], [0, 1, 2])
reg.coef_
reg.intercept_

