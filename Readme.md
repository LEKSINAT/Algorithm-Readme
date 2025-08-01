## 1. Reverse string #01
## Example:

| input | Output |
|----   |--------|
| Hello | olleH  | 
| banana| ananab |  

```python
text = "Hello Baby"
reverseText = ""
for index in range(1, len(text) + 1):
    reverseText += text[-index]
print(reverseText)

## result == byaB olleH
```  
## 2. Reverse string #02
## Example: 

```python
text = "Hello Baby"
lastIndex = len(text) - 1
reverseText = ""
for index in range(len(text)):
    reverseText += text[lastIndex - index]
print(reverseText)

## result == byaB olleH
```  
## 3. Find Index of odd number
## Example :
| input    | Output |
|--------- |--------|
| [2,3,4,5]| [1,3]  | 

```python
arr = [5,7,8,4,3]
indexOfOdd = []
for i in range(len(arr)):
    if arr[i] % 2 == 1:
        indexOfOadd.append(i)
print(indexOfOdd)

## result == [0, 1, 4]
``` 
## 4. Average of number in list
## Example :
| input        | Output |
|---------     |--------|
| [5, 7, 8,4,3]|   5.4  |

```python
arr = [5,7,8,4,3]
average = 0
sum = 0
for value in arr:
    sum += value
average = sum / len(arr)
print(average)

## result == 5.4
``` 

## 5. Display name in arr
## Example :

```python
arr =[
    {'name': 'bopha', 'age': 18},
    {'name': 'thida', 'age': 12},
    {'name': 'kanha', 'age': 16},
]
for dics in arr:
    print(dics['name'])

## Output
#bopha 
#thida
#kanha
``` 

## 6. Sum numbers
## Example :

| input        | Output |
|---------     |--------|
| [5, 7, 8,4,3]|   27 |

```python
 arr = [5, 7, 8,4,3]
sum = 0
for value in arr:
sum += value
print(sum)

## Output: 27
``` 

## 7. Display Even number
## Example :

| input        | Output |
|---------     |--------|
| [5, 7, 8,4,3]|   8, 4 |

```python
 arr = [5, 7, 8,4,3]
for value in arr:
    if value % 2 == 0
        print(value)
## Output: 8 4
``` 

## 8. Display Minimum number
## Example :

| input             | Output |
|---------          |--------|
| [10 ,40, 20, 4, 3]|  3 |

```python
 arr = [10 ,40, 20, 4, 5]
 for value in arr:
    if value < min:
        min = value
print(min)
## Output: 3
``` 
## 9. Move one step to right 
## Example :

| input          | Output |
|---------       |--------|
| [0, 0, 1, 0, 0]| [0, 0, 0, 1, 0]|

```python
arr =  [0, 0, 1, 0, 0]
isFound = False
for i in range (len(arr) -1):
    if arr[j]== 1 and not isFound:
        arr[i] = 0
        arr[j + 1] = 1
        isFound = True
print(arr)
## Output: [0, 0, 0, 1, 0]
```

## 10. Move one step to left 
## Example :

| input          | Output |
|---------       |--------|
| [0, 0, 1, 0, 0]| [0, 1, 0, 0, 0]|

```python
arr =  [0, 0, 1, 0, 0]
isFound = False
for i in range (len(arr) -1):
    if arr[j]== 1 and not isFound:
        arr[i] = 0
        arr[j - 1] = 1
        isFound = True
print(arr)
## Output: [0, 1, 0, 0, 0]
```

## 11. Display Maximum number
## Example :

| input             | Output |
|---------          |--------|
| [10 ,40, 20, 4, 3]|  40|

```python
 arr = [10 ,40, 20, 4, 5]
 for value in arr:
    if value < max:
        max = value
print(max)
## Output: 40
``` 

## 12. Sum value in row
## Example :

```python
 arr2D = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9],
 ]
sum = 0
arr = []
for row in range(len(arr2D)):
    for col in range(len(arr2D[row])):
        sum += arr2D[row][col]
    arr.append(sum)
    sum = 0
print(arr)
## Output: 40
``` 




