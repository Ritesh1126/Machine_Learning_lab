# Machine_Learning_lab
This For College use 
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

sns.set_style('darkgrid')

import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))

sales = pd.read_csv("/retail_sales_dataset.csv")
sales.head()
