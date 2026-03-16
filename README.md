# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

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
```
import matplotlib.pyplot as plt
import numpy as np

# Simple Example
x = np.arange(0,10)
y = np.arange(11,21)

# Scatter Plot
plt.scatter(x,y)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.show()

# Line Plot
y = x*x
plt.plot(x,y)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2D Diagram')
plt.show()

# Subplots
plt.subplot(2,2,1)
plt.plot(x,y)

plt.subplot(2,2,2)
plt.plot(x,y)

plt.subplot(2,2,3)
plt.plot(x,y)

plt.subplot(2,2,4)
plt.plot(x,y)

plt.show()

# Sine Wave
x = np.arange(0, 4 * np.pi, 0.1)
y = np.sin(x)

plt.title("Sine Wave Form")
plt.plot(x,y)
plt.show()

# Sine and Cosine Subplots
x = np.arange(0, 5 * np.pi, 0.1)
y_sin = np.sin(x)
y_cos = np.cos(x)

plt.subplot(2,1,1)
plt.plot(x,y_sin)
plt.title('Sine')

plt.subplot(2,1,2)
plt.plot(x,y_cos)
plt.title('Cosine')

plt.show()

# Bar Graph
x = [2,8,10]
y = [11,16,9]

x2 = [3,9,11]
y2 = [6,15,7]

plt.bar(x,y)
plt.bar(x2,y2)
plt.title("Bar Graph")
plt.xlabel("X axis")
plt.ylabel("Y axis")
plt.show()

# Histogram
a = np.array([22,87,5,43,56,73,55,54,11,20,51,5,79,31,27])

plt.hist(a)
plt.title("Histogram")
plt.show()

# Box Plot
data = [np.random.normal(0, std, 100) for std in range(1,4)]
plt.boxplot(data)
plt.show()

# Pie Chart
labels = ['sepal_length','sepal_width','petal_length','petal_width']
sizes = [215,130,245,210]

plt.pie(sizes, labels=labels, autopct='%1.1f%%')
plt.axis('equal')
plt.show()
```
<img width="800" height="647" alt="Screenshot 2026-03-16 215524" src="https://github.com/user-attachments/assets/585cd489-b54c-40b4-a522-66f1458fa735" />
<img width="768" height="543" alt="Screenshot 2026-03-16 215532" src="https://github.com/user-attachments/assets/ceea6212-e05f-4b69-a62e-27ebae8f35ba" />
<img width="792" height="531" alt="Screenshot 2026-03-16 215538" src="https://github.com/user-attachments/assets/4af56e95-1b43-4086-87fb-0e02570a7801" />
<img width="812" height="552" alt="Screenshot 2026-03-16 215548" src="https://github.com/user-attachments/assets/22657b25-9782-4032-adc5-aff26e1fa23d" />
<img width="858" height="545" alt="Screenshot 2026-03-16 215554" src="https://github.com/user-attachments/assets/500a7266-e83e-4fc7-80a0-e71523540cad" />
<img width="813" height="542" alt="Screenshot 2026-03-16 215603" src="https://github.com/user-attachments/assets/d5e63f1a-b431-4147-8739-16b2ce5143c6" />
<img width="790" height="586" alt="Screenshot 2026-03-16 215611" src="https://github.com/user-attachments/assets/d7dc5392-e200-4e60-ae8b-64940ddc005d" />
<img width="757" height="473" alt="Screenshot 2026-03-16 215622" src="https://github.com/user-attachments/assets/50e2238e-75d6-44be-8488-08a3cc837e5e" />

# Result:
Different data visualization plots such as scatter plot, line plot, bar chart, histogram, box plot, and pie chart were successfully created using the Matplotlib library in Python.
# PDF FILE:
[vertopal.com_iris EX-5.pdf](https://github.com/user-attachments/files/26030549/vertopal.com_iris.EX-5.pdf)


