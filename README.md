# Starbucks

#项目简介

这个数据集由一个模拟程序创建，该程序主要模拟了人们如何做出购买行为，以及这些购买行为将受到促销活动的影响。
基本任务是利用数据来分辨哪类人群最可能对某种推送做出响应，以及如何更好地使用每种推送。

#用到的包
import pandas as pd
import numpy as np
import math
import json
from sklearn.cross_validation import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score
from sklearn.ensemble import BaggingClassifier
# % matplotlib inline
from matplotlib import pyplot as plt
from sklearn.tree import DecisionTreeClassifier
from sklearn.preprocessing import StandardScaler
from sklearn import  preprocessing
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error,r2_score
import seaborn as sns