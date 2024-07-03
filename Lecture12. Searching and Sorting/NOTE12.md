# Search algorithms
Implicit and explicit

## Linear search
brute force search. The list doesn't have to be sorted. O(n)

## Bisection search
the list must be sorted. sorting+O(logn)
sorting > n

## Amortized cost
SORT + K*O(logn) < K*O(n)


# Sort algorithms

## Monkey sort(bogosort)
<img width="550" alt="截屏2024-06-04 18 11 29" src="https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/795db27d-b82c-4f48-a564-725a37e050b3">

## Bubble sort
1. Compare consecutive pairs of elements
2. Swap elements in pairs so the smaller is the first
3. When reach the end of the list, start over again
4. stop when no more swaps have been made
5. at most n pass: largest goes to the end of the list each time

<img width="650" alt="截屏2024-06-04 18 20 04" src="https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/86b904c1-9823-44f1-bc5e-b31625617bb1">

*Even if your flag variable is false the while loop will continue until its finished before it checks if active is still true. Instead you can use the keyword break (instead of active = false) which will immediately stop your while loop.

<img width="650" alt="截屏2024-06-04 21 40 31" src="https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/7ebb9d89-87df-414a-8296-141b41dd72c7">

## Selection sort

<img width="650" alt="截屏2024-06-04 22 35 54" src="https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/ad6fa6f6-efd3-4fe3-aaf3-0bb8e613ce94">

1. first step
   extract minimum element
   swap it with the element at index 0
2. subsequent step
   in the remaining sublist, extract the minimum element
   swap it with the element at index 1
3. keep the left portion of the list sorted
   at this step, the first i elements in the list are sorted
   all other elements are bigger than the first i elements


## Merge sort

Divide and conquer.
1. Split the list in half until reaching the smallest pieces in each branch.
2. Compare and sort the pieces.
3. Merge and compare the smallest in two pieces.
4. Append the rest after comparison.

<img width="650" alt="截屏2024-07-03 09 46 40" src="https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/deedfc60-9ac8-4749-b39a-be8615406fed">

<img width="650" alt="截屏2024-07-03 09 47 00" src="https://github.com/LetongLi/1.6.100A-Introduction-to-Computer-Science-Programming-in-Python/assets/144520045/4062e650-087c-4ef1-a80e-d8ecd886a77f">




