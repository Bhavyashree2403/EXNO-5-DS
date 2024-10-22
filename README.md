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
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![Screenshot 2024-10-17 113800](https://github.com/user-attachments/assets/510e0cb6-5a9c-4ad1-8a2f-1d948a36f124)
```
import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```
![Screenshot 2024-10-17 113812](https://github.com/user-attachments/assets/e9bc879f-0589-4c10-9ad7-9c2a64b3e004)

```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![Screenshot 2024-10-17 113823](https://github.com/user-attachments/assets/9ec29f7d-56ea-4d5d-bf89-c3d0502b40bc)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')

plt.show()
```
![Screenshot 2024-10-17 113835](https://github.com/user-attachments/assets/2a62ffb2-4574-4ce3-8c3d-1b298772861f)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![Screenshot 2024-10-17 113847](https://github.com/user-attachments/assets/3fc7eac1-9741-493e-b309-5a88e5f5f4ff)
```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
```
![Screenshot 2024-10-17 113857](https://github.com/user-attachments/assets/d308e055-3ff5-49a9-9265-e6da09e1d6e5)
```
years=range(2000,2012)
apples= [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![Screenshot 2024-10-17 114000](https://github.com/user-attachments/assets/530a5568-26ea-4d67-8af6-c0ddc8022cb0)
```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```
![Screenshot 2024-10-17 114023](https://github.com/user-attachments/assets/c6fba8b1-9516-4031-a0e5-633b003abfd8)
```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![Screenshot 2024-10-17 114032](https://github.com/user-attachments/assets/38d3c625-4117-4619-b4fd-eea0f9a2e384)
```
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yeild of Oranges (tons per hectare)");
```
![Screenshot 2024-10-17 114050](https://github.com/user-attachments/assets/c35138c5-02d5-49d9-bffb-9a695ac2d1aa)
```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```
![Screenshot 2024-10-17 114059](https://github.com/user-attachments/assets/f8f210ea-17cc-45ff-8977-f9a52f32dc5e)
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![Screenshot 2024-10-17 114109](https://github.com/user-attachments/assets/6fb3caae-cbc9-485f-8097-f345b84f84ad)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![Screenshot 2024-10-17 114120](https://github.com/user-attachments/assets/c04a9b25-9b8e-4804-b724-2cfbe99c13e6)
```
y
```
![Screenshot 2024-10-17 114126](https://github.com/user-attachments/assets/f54d037d-22a4-4eab-9c40-c14e2eeb499d)
```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![Screenshot 2024-10-17 114138](https://github.com/user-attachments/assets/d10feeb6-ff9f-4185-9bc9-e0b9fba57bb9)
```
y=x*x
y
```
![Screenshot 2024-10-17 114148](https://github.com/user-attachments/assets/478b3f57-0702-4eb7-add8-f8932fa32e33)
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![Screenshot 2024-10-17 114205](https://github.com/user-attachments/assets/2d93f29c-6dd2-421b-b832-4bac234312af)
```
np.pi
```
![Screenshot 2024-10-17 114214](https://github.com/user-attachments/assets/e3a68e78-49f0-4a44-8c99-c99fe771b8ff)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![Screenshot 2024-10-17 114223](https://github.com/user-attachments/assets/fe01effb-e2b8-452f-9f5a-3043ea7b63b7)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color="red")
plt.plot(x,y2,color="black")
plt.legend(['y1','y2'])
plt.show()
```
![Screenshot 2024-10-17 114233](https://github.com/user-attachments/assets/07f9a0a1-e466-440f-b6df-04909085f120)
```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![Screenshot 2024-10-17 114245](https://github.com/user-attachments/assets/2a1ab521-f72f-4ddf-ac9a-ec87a07c51e9)
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,11]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![Screenshot 2024-10-17 114256](https://github.com/user-attachments/assets/644c1175-5a1c-4ac0-b752-5a88e0ac101e)
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('My histogram')
plt.show()
```
![Screenshot 2024-10-17 114306](https://github.com/user-attachments/assets/f9313767-0601-4a14-bd6c-8e24c01e6263)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![Screenshot 2024-10-17 114314](https://github.com/user-attachments/assets/19bc21e0-a072-496c-bae7-600626ccba66)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box plot')
```
![Screenshot 2024-10-17 114324](https://github.com/user-attachments/assets/26c8687a-5096-4c35-9de3-59b3a71254a4)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,
autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![Screenshot 2024-10-17 114333](https://github.com/user-attachments/assets/a433f104-5952-47d2-bb14-0564ac20b3fa)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,
        startangle=90,shadow=True,explode=(0,0,0.1,0),
        radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![Screenshot 2024-10-17 114344](https://github.com/user-attachments/assets/42bc1c65-c921-4614-8bec-a9b3e73215c6)


# Result:
  Performing Data Visualization using matplot python library for the given datas is successful.
