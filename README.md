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

 <img width="793" height="588" alt="image" src="https://github.com/user-attachments/assets/64461d71-4ea1-4ca2-b262-62fd8d28f006" />

<img width="762" height="582" alt="image" src="https://github.com/user-attachments/assets/426aed26-538a-4106-a4d5-b5005502a727" />


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

 <img width="753" height="573" alt="image" src="https://github.com/user-attachments/assets/83768c28-7136-4f54-8287-1b260d5845f4" />

<img width="778" height="630" alt="image" src="https://github.com/user-attachments/assets/8bb4662b-7bf4-481b-9bd2-caa456f40f19" />

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


 <img width="621" height="571" alt="image" src="https://github.com/user-attachments/assets/cb2e4027-97b9-4e59-88cc-c8e40dfb054a" />

<img width="605" height="563" alt="image" src="https://github.com/user-attachments/assets/81081fb3-cecc-4cab-b243-10b7f921babd" />

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

 <img width="765" height="573" alt="image" src="https://github.com/user-attachments/assets/07b755d6-9502-47d2-8cb3-8735d044c0bf" />


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


 <img width="774" height="625" alt="image" src="https://github.com/user-attachments/assets/83428313-3d9d-4bc7-a9ac-9d2026d064ce" />



```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()



```

 <img width="731" height="572" alt="image" src="https://github.com/user-attachments/assets/4e3ce6bf-8d0d-4c2e-9c2c-b5f6c3962eb1" />


```


 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data



```

 <img width="776" height="490" alt="image" src="https://github.com/user-attachments/assets/b17096a6-0b0b-494f-adbc-4cccd27a796b" />


```


 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')



```


 <img width="782" height="661" alt="image" src="https://github.com/user-attachments/assets/42c84d87-e781-4cca-bb3c-17751b32036e" />

## RESULT
Thus, python program to perform stop and wait protocol was successfully executed.
