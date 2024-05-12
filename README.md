# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Algorithm:
Step 1:
Read the csv file.

Step 2:
Get the value of X and y variables.

Step 3:
Create the linear regression model and fit.

Step 4:
Predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm cube.

Step 5:
Print the predicted output.
## Program:
```
Developed by: SOWMYA BADONI
Reg.No: 212223230211
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))
```
## Output:
![328384259-23ae9c55-f636-4dc6-aa94-6c222b7ab73d](https://github.com/sowmya-badoni/Multivariate-Linear-Regression/assets/152136324/758c1854-692f-4141-92db-f4787ac98489)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
