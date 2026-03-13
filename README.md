# EX NO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
## Name : HARI PRASATH E
## Ref No : 25007799
# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 Include the necessary coding and corresponding screenshots
```
import matplotlib.pyplot as plt
x=[0,1,2,3,4,5]
y=[0,1,4,9,16,25]
plt.plot(x,y)
plt.show()
```
<img width="914" height="722" alt="image" src="https://github.com/user-attachments/assets/7bbb4af4-be07-48de-8f27-625da0c70f1f" />

```
import matplotlib.pyplot as plt
x= [0,1,2,3,4,5]
y=[0,1,4,9,16,25]
plt.plot(x,y)
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.show()
```
<img width="935" height="858" alt="image" src="https://github.com/user-attachments/assets/7a2da8e4-ea2c-412d-822e-8a70aa2cd270" />

```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1, label="line1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2, label="line2")
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.title("COMPARISON OF TWO LINES")
plt.legend()
plt.show()
```
<img width="684" height="838" alt="image" src="https://github.com/user-attachments/assets/202d6dd3-aaee-4341-a04b-c0e3cc76a013" />


```
import matplotlib.pyplot as plt
x= [0,1,2,3,4,5]
y=[2,4,6,8,10,12]
plt.plot(x,y)
plt.xlim(1,5)
plt.ylim(1,16)
plt.show()
```
<img width="699" height="696" alt="image" src="https://github.com/user-attachments/assets/76994642-1f1b-4d8d-a71f-3892d5b46cb5" />


```
import matplotlib.pyplot as plt
import numpy as np
x= [1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between (x,y1, color='black')
plt.fill_between (x,y2,color='magenta')
plt.plot(x,y1, color="red")
plt.plot(x,y2, color="black")
plt.legend(['y1','y2'])
plt.show()
```
<img width="690" height="837" alt="image" src="https://github.com/user-attachments/assets/e6cf018f-e2d6-4926-b150-fefb5f7c09d3" />


```
import matplotlib.pyplot as plt
import numpy as np
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.stackplot(x, y1, y2, y3, colors=['red', 'pink', 'purple'], labels=["line1", "line2", "line3"])
plt.legend(loc="upper left")
plt.show()
```
<img width="677" height="617" alt="image" src="https://github.com/user-attachments/assets/96cc2202-783a-43bf-b6e0-477f377a3c99" />

# Result:
Thus The Implementation of Data visualization using MatplotLIB is Verified.....
