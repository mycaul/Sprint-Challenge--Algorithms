#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I
a) O(N)
Time taken will grow along with input for loop, the relationship is linear


b) O(n log n) 
The outer loop will scale as n grows. The inner loop will scale faster than linear time as its input
increases.


c) O(N) 
This relationships is also linear

## Exercise II
Use binary search

 -Find total amount of floors and split them in half.
 - Does the egg breaks at this mid point?
 - Yes egg breaks, traverse down the lower floors until egg does not break
 - No egg does not break, traverse up the higher floors until target floor.

 
 My solution rc on average is O(log n)
