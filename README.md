#Siya Ram


#code for linear regression without Cost function

import numpy as np
import matplotlib.pyplot as plt

x_train = np.array([1.0,2.0])
y_train = np.array([300.0,500.0])

i = 0

x_i = x_train[i]
y_i = y_train[i]

def compute_model_output(x, w, b):

    m = len(x)
    f_wb = np.zeros(m)
    for i in range(m):
        f_wb[i] = w * x[i] + b

    return f_wb
    
w = 200
b = 100
x_i = 1.2
cost_1200sqft = w * x_i + b

print(f"${cost_1200sqft:.0f} thousand dollars")
