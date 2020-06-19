#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) 0(n) The variable is increased by n^2 each loop until it reaches n^3. It will take n^3 / n^2 passes before the while condition becomes false.

b) 0(n log n) The while loop is nested in the for loop and assigns j *= 2 while j < n. As the size of the input increases, the runtime will grow at a slightly faster rate.

c) 0(n) In this recursive function, the input "bunnies" would be considered n. It decrements by 1 and no other logic performed will take additional time until the base case is reached.

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

while length of building > 1 floor: find middle of building drop egg if egg breaks: next building starts at previous bottom and ends at current midpoint if not breaks: next building starts at current midpoint and ends at previous top

This is a binary search because it starts searching in the middle, eliminating half of the data set with each pass. The time complexity would be 0(log n).


