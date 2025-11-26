# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
 Developed by: AADHITHYA.V
 RegisterNumber: 25018761
 Program to implement univariate Linear Regression to fit a 
straight line using least squared 
import numpy as np 
import matplotlib.pyplot as plt 
x=np.array(eval(input())) 
y=np.array(eval(input())) 
x_mean=np.mean(x) 
y_mean=np.mean(y) 
num=0 
denom=0 
for i in range(len(x)): 
num+=(x[i]-x_mean)*(y[i]-y_mean) 
denom+=(x[i]-x_mean)**2 
m=num/denom 
b=y_mean-m*x_mean 
print(m,b) 
y_predicted=m*x+b 
print(y_predicted) 
plt.scatter(x,y) 
plt.plot(x,y_predicted,color='red') 
plt.show()

## Output:
![ML 2  PIC](https://github.com/user-attachments/assets/8be7308c-bbec-40e5-bb58-f5a32688a1a3)


## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
