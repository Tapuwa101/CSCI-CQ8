Staircase:

Time Complexity:
We can determine this by looking at how many nested loops we have in the fuction.
The outer loop runs n times and The inner loops have constant time complexity since they iterate a fixed number of times (equal to w and y.Thus time complexity is O(n).

Space Complexity: O(1)

Alternating characters 

This recursive definition uses a helper function (minDeletions) that takes the current index, the last character seen, and calculates the minimum deletions. 

we have a base case that checks if the index reaches the end of the string, and the recursion progresses through the string, considering whether to delete the current character or keep it based on the last character seen. 
