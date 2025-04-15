# blind-12-75
Number of 1 bits 


Simple program ig.
Assume a variable result=0.
key concept here is the usage of '&' and operator .
if  (n & 1)==1  , that means we have a set bit( binary '1') , and hence increase the count. i.e result+=1.
update the number , n>>1 . i.e right shift , so that we check for other bits.
We repeat this process , until we have a valid number . ( i.e n!=0)
Time complexity : O(log n) ig we need log n bits to represent a number n. and all those bits will be checked upon to find out the count. 
Space complexity: O(1)
