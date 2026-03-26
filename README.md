# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>
Open new file in jupiter notebook.

### Step2
<br>
Import the neccessary libraries and load the data.

### Step3
<br>
Define input (Volume, Weight) and output (CO2)

### Step4
<br>
Create regression model

### Step5
<br>
Predict for new input

## Program:
```
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[["Volume","Weight"]]
y=df["CO2"]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))

```
## Output:
<img width="816" height="362" alt="Screenshot 2026-03-26 085330" src="https://github.com/user-attachments/assets/5abe0746-f9ce-48a7-bc23-15801b15ff74" />


### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
