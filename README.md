# Insertion Sort Project - www.patika.dev

## Question 1
### First part
Original array: [22, 27, 16, 2, 18, 6]
1. Since 2 is the smallest number; change 22, which is first element of the array, with 2. -> [2, 27, 16, 22, 18, 6]
2. Now check for the second element which is 27 and exclude "2" -> [2, 6, 16, 22, 18, 27]
3. The third element -> [2, 6, 16, 22, 18, 27]. Since there is no number smaller than 16, the order did not change.
4. The fourth element -> [2, 6, 16, 18, 22, 27]

After fourth step, since the array is sorted, there is nothing else to do.

### Second part
Big-O Notation: n! = n*(n+1)/2) = (n^2+n)/2 -> O(n^2)

### Third part
- Worst case: O(n^2)
- Average case: O(n^2)
- Best case: O(n)

### Fourth part
After insertion sort process, since 18 is somewhere in the middle, we consider that as average case.

## Question 2
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]
