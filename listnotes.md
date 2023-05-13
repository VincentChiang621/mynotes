# Lists
Lists are mutable, ordered, allow duplication, and different data types

heres how you can initialize one...

```py
#this is a valid list
myList = ["banana", "apple", "cherry", "apple", 5, True]

#access the list with []
print(mylist[1]) #prints apple
print(mylist[-1]) #prints True
```

you can also create a 2D list
```py
myList = [["fruit", "banana"], ["animal", "bear"]]
print(myList[-2]) #prints ['fruit', 'banana']
```
## **List Functions**
adding elements to list

-list.append(element)
```py
#initialize empty list
animals = []

#add 'bears' to animals
animals.append("bears")

#add 'tigers' to animals
animals.append("tigers")

print(animals) #prints ['bears', 'tigers']
```
*note: items are printed in order you inserted*

however, you could insert items in a given index

-list.insert(index, element)
```py
animals = ['bears', 'tigers']

#insert 'eleplants' at index 1
animals.insert(1, 'elephants')

print(animals) # prints ['bears', 'elephants' 'tigers']
```
you can also concatenate 2 lists...

-list.extend(another_list)
```py
list1 = [1, 3, 6]

list1.extend([34, 64])

print(list1) #prints [1, 3, 6, 34, 64]
```