#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)On, the bigger the longer this will take to reach a conclusion in the while loop


b)O(n * logN), the total is a linear operation only increasing, j multiplies by 2 in every iteration which makes it exponentially
close the distance between it and whatever n is.  


c)On, recursive function with no loop only dependant on n

## Exercise II

We would use binary search to find the center floor of the building using floor division.
We will divide and conquer, dropping an egg from the middle and seeing if it cracks. If it cracks, we will not go up only down.
If it doesn't crack we will go up by finding the center of the top half of the building.
Your eggs are important! We will then find the center of the remaining floors, and drop an egg from that center. If an
egg does not break we will find the next center going up and drop an egg, repeating this until an egg cracks.

This is O(logN)

