## 1. Reverse string
## Example:

| input | Output |
|----   |--------|
| Hello | olleH  | 
| banana| ananab |  

```python
text = "Hello Baby"
reverseText = ""
for index in range(1, ken(text) + 1):
    reverseText += text[-index]
    print(reverseText)

## result == byaB olleH
```  
## 2. Find Index of odd number
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
## 3. Average of number in list
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

## 4. Display name in arr
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

## 5. Sum numbers
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



