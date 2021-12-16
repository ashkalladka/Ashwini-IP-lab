```python
# Using for loop

fruits = ["apple", "mango", "cherry"]
for x in fruits:
  print(x)
```

    apple
    mango
    cherry
    


```python
for x in "Ash":
  print(x)
```

    A
    s
    h
    


```python
#Exit the loop when x is "mango":

fruits = ["apple", "mango", "cherry"]
for x in fruits:
  print(x)
  if x == "mango":
    break
```

    apple
    mango
    


```python
#Exit the loop when x is mango but break comes before the print
fruits = ["apple", "mango", "cherry"]
for x in fruits:
  if x == "mango":
    break
  print(x)
```

    apple
    


```python
# Print "Ashwini" 5 times
for number in range(5):
    print("Ashwini")
```

    Ashwini
    Ashwini
    Ashwini
    Ashwini
    Ashwini
    


```python
list=[1,2,3,4,5,6,7,8,9,10]
n=5
for i in list:
    if i%2==0:
        c=n*i
        print(c)
        print ("Multiples of 5")
    
```

    10
    Multiples of 5
    20
    Multiples of 5
    30
    Multiples of 5
    40
    Multiples of 5
    50
    Multiples of 5
    


```python
week=['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday']

for x in week:
    if x=='Sunday':
     continue
    if x=='Monday':
     continue
    if x=='Tuesday':
     continue
    if x=='Saturday':
     continue
    print(x)
            
```

    Wednesday
    Thursday
    Friday
    


```python
marks = 60
if marks >= 90:
  grade = 'A'
elif marks >= 80:
  grade = 'B'
elif marks >= 70:
  grade = 'C'
elif marks >= 60:
  grade = 'D'
else:
  grade = 'F'
print(grade)
```

    D
    


```python
weeks=['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday']

for x in weeks:
    if x=='Sunday':
     print('No Harish sir class in Sunday')
     continue
    if x=='Monday':
     print('No Harish sir class in Monday')   
     continue
    if x=='Tuesday':
     print('No Harish sir class in Tuesday')   
     continue
    if x=='Saturday':
     print('No Harish sir class in Saturday')   
     continue
    print(x)
```

    No Harish sir class in Monday
    No Harish sir class in Tuesday
    Wednesday
    Thursday
    Friday
    No Harish sir class in Saturday
    No Harish sir class in Sunday
    


```python

```
