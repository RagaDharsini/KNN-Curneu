# KNN-Curneu
KNN Algorithm-Fruits Dataset
CurneuMedTech Innovations

TASK:
K-Nearest Neighbour Algorithm- Fruit Classification
DATASET:
	 
CODE:
import numpy as np
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
data = pd.read_csv("fruits.csv")
data.head()
one = data[data["fruit_label"] == "one"]
two = data[data["fruit_label"] == "two"]
three = data[data["fruit_label"] == "three"]
four = data[data["fruit_label"] == "four"]
plt.scatter(one.mass,one.width,one.height, color ="r" , label = "one", Alpha = 0.3) 
plt.scatter(two.mass,two.width,two.height, color ="g" , label = "two", Alpha = 0.3) 
plt.scatter(three.mass,three.width,three.height, color ="b" , label = "three", Alpha = 0.3) 
plt.scatter(four.mass,four.width,four.height, color ="y" , label = "four", Alpha = 0.3) 
plt.xlabel("mass")
plt.ylabel("width")
plt.legend()
plt.show()










 
