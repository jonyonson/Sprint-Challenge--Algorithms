#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)


b) O(n log(n))


c) O(n)

## Exercise II


- Begin by dropping the egg  from the halfway point of the building (`n // 2`)
- If the egg breaks, find a new halfway point between the current floor and the bottom of the building.
- If the egg does not break find a new halfway point between the current floor and the top of the building.
- Continue halfing the floors based on whether or not the egg breaks until you find `f`

The runtime complexity of this solution would be `O(log n)`
