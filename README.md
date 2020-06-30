## odd-index-Even-index
- We have Given a two list. 
- Create a third list by picking an odd-index element from the first list
- And even index elements from second.
## Sample code to find odd index elements & Even index elements
```sh
oddElements = listOne[1::2]
print("Element at odd-index positions from list one")
print(oddElements)
EvenElement = listTwo[0::2]
print("Element at even-index positions from list two")
print(EvenElement)
```
## Expected output
Element at odd-index positions from list one
[6, 12, 18]
Element at even-index positions from list two
[4, 12, 20, 28]
Printing Final third list
[6, 12, 18, 4, 12, 20, 28]
