# dsa-problem-solving-cheatsheet
This repository is for the quick overview of important Data Structures and Algorithms concepts

This is not a complete programming guide but more specifically designed for BEGINNER/INTERMEDIATE level programmers only to help them overlook very important concepts related to Data Structures and Algorithms before interviews or for periodic reviews.

Concepts Included:  
## 1. Data Structures
i) Arrays  
ii) Hashtables  
iii) Linked List  
iv) Queue  
v) Stack  
vi) Tree  
vii) Trie  
viii) Graph  
 
## 2. Sorting Algorithms  
i) Bubble Sort  
ii) Selection Sort  
iii) Insertion Sort  
iv) Merge Sort  
v) Quick Sort  
vi) Heap Sort  
vii) Counting Sort  
viii) Radix Sort  

# 1. Data Structures

## 1.1 Arrays

#### Static Array    
Lookup - O(1)  
Append - O(1)  
Insert - O(n)  
Delete - O(n)  

#### Dynamic Array  
Lookup - O(1)  
Append - O(1)* : O(n) in case of reallocation of memory *(while other languages handles memory allocation by themselves, C has realloc() function)*  
Insert - O(n)  
Delete - O(n)  

#### String Question
Convert String to Array  
**C**          : In C string is by itself stored as an array of characters. Hence its characters can be directly accessed by indexing.  
**C#, Java**   : toCharArray()  
**Python**     : list()  
**JavaScript** : split()  

#### Searching
Is array sorted?  
  - If **Yes**, Binary Search : O(logN)
  - IF **No**
    - Will Sorting make solution efficient?   
      - If **Yes**, Sorting Algorithms
      - If **No**, Linear Search : O(n)
