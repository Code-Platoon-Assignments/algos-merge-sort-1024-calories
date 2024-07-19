# algos-merge-sort-1024-calories

Daldus Bumbledore and Severina Snap have finally done it! They've joined forces, combining Daldus's 32 Flavors of Ice Cream Franchise, and Severina's 64 Slices of Pizza Empire, to form the indomitable franchise 1024 Calories.

They are now looking at all their combined store locations across the globe, and trying to figure out which ones to merge first. And, they need your help.

They need you to write a merge sort algorithm that will look at the list of possible locations and, in order from greatest to least, sort them by the number of ice cream sales, since summer is coming up and they want to start convering the most profitable ice cream stores first.

Your sort algorithm must return a sorted list of dictionaries (same format as the input data) ordered by `ice_cream_sales` from greatest to least.

## Stretch Goal

Modify your merge sort algorithm to accept an argument named `compare`. You should pass this argument a function, and, the algorithm should use it for the actual comparison step.

With this flexibility, you can write one `compare` function that sorts by profitable ice cream stores, and another that sorts by profitable pizza locations.

**Hint: Look at the Merge Sort Implementation of Page 134 of [Introduction to Computation and Programming Using Python](https://drive.google.com/file/d/10G1YTeICaiLE0HmLsXvTmp_cClaMAgUM/view?usp=sharing) -- that implementation passes a `compare` function as an argument. Don't worry about making your implementation recursive, yet.**

## Stretch Stretch Goal

Have your algorithm print something every time it 'divides', and every time it 'conquers' (sorts and combines two sublists). Write tests against those print statements to test that your algorithm implements correctly.