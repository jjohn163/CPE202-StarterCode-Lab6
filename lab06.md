Spring 2020 Lab 6

**Lab 6: Basic Comparison Sorts**

A comparison sort is a type of sorting algorithm that compares elements in a list (array, file, etc) using a comparison operation that determines which of two elements should occur first in the final sorted list. The operator is almost always a **total order** :

1. a ≤ a for all a in the set

2. if a ≤ b and b ≤ c then a ≤ c (transitivity)

3. if a ≤ b and b ≤ a then a=b

4. for all a and b, either a ≤ b or b ≤ a // any two items can be compared (makes it a total order)

In situations where three does not strictly hold then, it is possible that a and b are in some way different and both a ≤ b and b ≤ a; in this case either may come first in the sorted list. In a **stable sort** , the input order determines the sorted order in this case.

A metaphor for thinking about comparison sorts in the abstract is that someone has a set of unlabeled weights and a balance scale. Their goal is to line up the weights in order by their weight without any information except that obtained by placing two weights on the scale and seeing which one is heavier (or if they weigh the same).

The following link is helpful.

Comparison Sorting Visualizations: https://www.cs.usfca.edu/~galles/visualization/ComparisonSort.html

Your goal for this lab is to implement simple versions of Insertion Sort - **insertion\_sort(alist)**, Selection Sort - **selection\_sort(alist),** that will sort an array of integers and **count the number of comparisons**. Include your test cases as lists in the same file as your functions. Each function takes as input a list of integers, sorts the list counting the comparisons at the same time, **and returns the number of comparisons**. After the function completes, the " **alist**" should be sorted.



**Also include a comment with your test cases explaining why the testcases for the worst case are the worst case!**

