# Project 2 - Merge Sort
#### [ 16, 21, 11, 8, 12, 22 ] -> Merge Sort
#### 1. Write the stages of the above array according to the sort type.  
##### Divide Stages  
First Stage:   
[ 16, 21, 11] - [ 8, 12, 22 ]  
Second Stage:  
[ 16, 21 ] - [ 11 ] - [ 8, 12 ] - [ 22 ]  
Third Stage:  
[ 16 ] - [ 21 ] - [ 11 ] - [ 8 ] - [ 12 ] - [ 22 ]  
##### Merge Stages  
First Stage:    
[ 16, 21 ] - [ 11 ] - [ 8, 12 ] - [ 22 ]  
Second Stage:  
[ 11, 16, 21 ] - [ 8, 12, 22 ]  
Third Stage:  
[ 8, 11, 12, 16, 21, 22 ]  

#### 2. Write the Big-O notation.  
Divide Stages -> O(logn), Merge Stages -> O(n) => Big-O notation: O(nlogn)
