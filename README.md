# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
df=pd.read_csv('/content/BSE-BOM590111.csv')


x=df['Date'] 
y=df['Close'] 
plt.xlabel('Date')
plt.ylabel('Close Price')
plt.title('GOLD PRICE')
plt.plot(x,y)
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/b561ad0e-a956-4c80-ba8f-f339a614603e)






# RESULT:
Thus we have created the python code for plotting the time series of given data.
