# March Machine Learning Mania 2024(Kaggle Competition)
![image](https://github.com/user-attachments/assets/3a90bb28-55b6-48ab-95d3-627b6b967d05)

## Overview
This project is forecasting the outcomes of both the men's and women's 2024 collegiate basketball tournaments, a portfolio of brackets based on historical data. We are provided by data on historical NCAA games to forecast the outcomes of the Division 1 Men's and Women's basketball tournaments.
### Dataset Description
Each season there are thousands of NCAA basketball games played between Division I college basketball teams, culminating in March Madness®, the 68-team national championship that starts in the middle of March. We are provided with a large amount of historical data about college basketball games and teams, going back many years. Armed with this historical data, we can explore it and develop our distinctive ways of predicting March Madness® game outcomes. We can even evaluate and compare different approaches by seeing which of them would have done best at predicting tournament games from the past.

### Kaggle Competition details 
- Kaggle competition: [March Machine Learning Mania 2024](https://www.kaggle.com/competitions/march-machine-learning-mania-2024/overview)
- Dataset: [Data to predict](https://www.kaggle.com/competitions/march-machine-learning-mania-2024/data)
- You can also download by:
  ```
  kaggle competitions download -c march-machine-learning-mania-2024
  ```
### Libraries 
  *** All Analytic Libraries used to predict the model in Python 3 environment:**
  ```python
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score
from sklearn.metrics import log_loss
import sklearn
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.ensemble import RandomForestClassifier, GradientBoostingClassifier
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Dense
from tensorflow.keras.utils import to_categorical
from sklearn.preprocessing import StandardScaler
from sklearn.neighbors import KNeighborsClassifier

```
