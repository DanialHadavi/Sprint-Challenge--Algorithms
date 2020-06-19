#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) a = 0
while (a < n _ n _ n):
a = a + n * n
this has a runtime of O(n*3) loop runs based on how big n\*3 is.

b) sum = 0
for i in range(n):
j = 1
while j < n:
j \*= 2
sum += 1
this has a runtime of O(n) Linear time

c) def bunnyEars(bunnies):
if bunnies == 0:
return 0

      return 2 + bunnyEars(bunnies-1)
      this has a runtime of O(1) it only checks if bunnies exists and amount of bunnies does not effect the runtime

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

d) We can use binary search to minimize amount of broken eggs and the runtime would be O(log n)
