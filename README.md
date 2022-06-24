# Greedy
I will be posting some good greedy problems


Key Advice :- For greedy, first think is there any way that is optimal for all, and then prove your intuition using contradiction.

https://usaco.guide/CPH.pdf#page=67

# Tasks and deadline given start and endtime -> maximum number of activitites. 
-> Here, we will sort by end time. and now its time to take activity only if the start time is grater than end time. 

# duration and deadline given, 
Here, suppose you have queue which has n element and a variable that tells us the minimum distance so far
Now, if the current element fits in then okay other wise we have to remove the one that costs us the maximum.

# Meeting room required. 
add start time by +1 and end by -1 and the maximum sum will be the maximum number of rooms required.
