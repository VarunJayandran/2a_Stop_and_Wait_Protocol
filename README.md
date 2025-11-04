# 2a_Stop_and_Wait_Protocol
## AIM 
To write a python program to perform stop and wait protocol
## ALGORITHM
1. Start the program.
2. Get the frame size from the user
3. To create the frame based on the user request.
4. To send frames to server from the client side.
5. If your frames reach the server it will send ACK signal to client
6. Stop the Program
## CODING AND OUTPUT
```
 import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt

 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
 
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
```
 <img width="806" height="527" alt="image" src="https://github.com/user-attachments/assets/6ee91d4b-f876-416b-b7d5-93666fef77ef" />

<img width="767" height="540" alt="image" src="https://github.com/user-attachments/assets/899df6f7-361f-4a99-aa70-2bba62cde54f" />

```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
 
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```
<img width="787" height="513" alt="image" src="https://github.com/user-attachments/assets/f04722e4-44ae-4f91-83f5-71d9eda5f821" />

<img width="820" height="557" alt="image" src="https://github.com/user-attachments/assets/81e28d31-6b3b-4942-83d7-4eba0e1464f6" />

```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```


<img width="699" height="494" alt="image" src="https://github.com/user-attachments/assets/991551da-84ad-4b03-a05a-b7e106e0c011" />

<img width="783" height="500" alt="image" src="https://github.com/user-attachments/assets/7fb90d61-0017-4edf-a85d-85ef828651f1" />

```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]

 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```
<img width="744" height="576" alt="image" src="https://github.com/user-attachments/assets/fab2827f-f9d1-4640-bc60-2e179a792f16" />


```
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['red', 'green'] 
 c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()

```
<img width="743" height="532" alt="image" src="https://github.com/user-attachments/assets/b73c745b-d5f4-4946-8cbc-8733dd7c29e7" />

```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()

```
 <img width="766" height="449" alt="image" src="https://github.com/user-attachments/assets/db094abe-a764-484d-80bb-427ca0672342" />
 
```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```
 
<img width="750" height="454" alt="image" src="https://github.com/user-attachments/assets/cfe81b2a-aa72-4be6-b1fb-33bb0cbde990" />

```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```
 <img width="769" height="583" alt="image" src="https://github.com/user-attachments/assets/f2e04e89-925a-4eb8-badd-0bae069247a0" />


## RESULT
Thus, python program to perform stop and wait protocol was successfully executed.
