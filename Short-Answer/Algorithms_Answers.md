#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The runtime complexity is constant - 0(log n) 


b) The runtime complexity is linear - 0(n) - We are looping over n using a for loop so it is linear.


c) The runtime complexity is constant - 0(1) because the function calls itself once for every call we make to the function

## Exercise II

We can use binary search kind of algorithm to determine the floor from which the egg breaks. 
We will consider 0 as the start and n as the endpoint
We find the mid by adding the start and end and dividing by 2
Then we throw an egg from the mid floor and check if it breaks.
If the egg does not break then the start point will be the midpoint + 1 and the end point will be n
If the egg breaks then the start point will be 0 and the endpoint will be midpoint - 1
We keep doing this till we find the value of f - floor at which the egg breaks.

The time complexity for the algorithm is log n 

