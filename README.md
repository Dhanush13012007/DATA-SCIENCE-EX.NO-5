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

x = np.arange(20, 50)
y = np.arange(50, 80)
a = np.arange(80, 110)
b = np.arange(110, 140)

plt.scatter(x, y, c='b')
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title('Graph in 2D')
plt.show()


plt.plot(x, y, 'b*', linestyle='dashed', linewidth=1, markersize=10)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('2D Diagram')
plt.show()


plt.subplot(3, 2, 1)
plt.plot(x, y, 'r.')
plt.subplot(3, 2, 2)
plt.plot(x, y, 'b*')
plt.subplot(3, 2, 3)
plt.plot(x, y, 'yo')
plt.subplot(3, 2, 4)
plt.plot(x, y, 'g*')
plt.subplot(3, 2, 5)
plt.plot(x, y, 'r.--')
plt.subplot(3, 2, 6)
plt.plot(x, y, 'g*')


x = np.arange(1, 10)
y = x * x

plt.plot(x, y, 'ro')
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title('Graph')
plt.show()


x = np.arange(0, 6 * np.pi, 0.1)
y_sin = np.sin(x)
y_cos = np.cos(x)

plt.subplot(2, 1, 1)
plt.plot(x, y_sin, 'y-')
plt.title('Sine Wave')
plt.show()

plt.subplot(2, 1, 2)
plt.plot(x, y_cos, 'b-')
plt.title('Cos Wave')
plt.show()


x = [2, 4, 6]
y = [3, 5, 7]
x2 = [12, 14, 16]
y2 = [13, 15, 17]

plt.bar(x, y, color='b')
plt.bar(x2, y2, color='y')
plt.title("Bar Graph")
plt.show()


a = np.array([34, 65, 79, 90, 82, 10, 94, 39, 34, 92, 72, 49])
plt.hist(a)
plt.title("Histogram")
plt.show()


a = [np.random.normal(0, std, 100) for std in range(1, 4)]
plt.boxplot(a, vert=True, patch_artist=True)
plt.show()

plt.boxplot(a, vert=False, patch_artist=False)
plt.show()


labels = ['RCB', 'CSK', 'MI', 'SRH']
sizes = [250, 250, 250, 250]
colors = ['red', 'yellow', 'blue', 'orange']
explode = (0.4, 0, 0, 0)

plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%.1f')
plt.axis('equal')
plt.show()


```
<img width="678" height="440" alt="Screenshot 2026-05-25 214037" src="https://github.com/user-attachments/assets/905ee5de-d5e7-4d0d-80b8-9f59368774e0" />

<img width="632" height="451" alt="Screenshot 2026-05-25 214050" src="https://github.com/user-attachments/assets/7b54384f-b316-4038-8de0-60e3fd3009f7" />

<img width="580" height="455" alt="Screenshot 2026-05-25 214056" src="https://github.com/user-attachments/assets/0dbbfb7b-1df8-4ea2-970c-cb7fe39df382" />

<img width="718" height="443" alt="Screenshot 2026-05-25 214102" src="https://github.com/user-attachments/assets/f9d5da41-f6c7-4e00-86f3-a7b207c99a57" />

<img width="689" height="479" alt="Screenshot 2026-05-25 214108" src="https://github.com/user-attachments/assets/82e5df45-4a67-4380-b7be-bf507f96543f" />

<img width="713" height="439" alt="Screenshot 2026-05-25 214113" src="https://github.com/user-attachments/assets/eab2a9c0-7ec1-4c92-8431-11c4f330de9d" />

<img width="633" height="417" alt="Screenshot 2026-05-25 214133" src="https://github.com/user-attachments/assets/8ba6176e-0164-4aa3-893a-129ff8430d15" />

<img width="679" height="443" alt="Screenshot 2026-05-25 214118" src="https://github.com/user-attachments/assets/312a239f-b599-4f30-ac90-80a33d5c396c" />

<img width="620" height="431" alt="Screenshot 2026-05-25 214145" src="https://github.com/user-attachments/assets/6da8e331-93d4-4f10-8b1b-02a805dface1" />

<img width="566" height="358" alt="Screenshot 2026-05-25 214206" src="https://github.com/user-attachments/assets/0fea5c59-229b-4b66-aa61-adb91d56d8fe" />

# Result:
Thus the program is executed successfully.

