Answers to Questions:
1) LinkedList instead of an ArrayList in TestIterator
Removing a value will be easier because you already have the index in a LinkedList 
2) Using list.remove(Integer.valueOf(77))
This method will remove the cases of 77 within the list 
3) LinkedList instead of an ArrayList in TestList
Insertion will be quicker because you have access to the reference with the iterator

4) Running Times for AddRemove vs Access for LinkedList and ArrayList as SIZE gets bigger
AddRemove (SIZE = 10)
LinkedList - 34 ms
ArrayList - 47 ms
SIZE = 100 
L - 22
A - 50
SIZE = 1000
L - 30
A - 83
SIZE = 10000
L - 7
A - 33


Access (SIZE = 10) 
LinkedList - 12
ArrayList - 36
SIZE 100 
L - 18
A - 38
SIZE 1000 
L - 68
A - 45
SIZE 10000
L - 79
A - 43

Conclusions: 
As SIZE gets bigger the LinkedList performs better in adding and removing elements and ArrayList performs better in Accessing elements. 
