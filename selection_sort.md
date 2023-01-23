## Project 1
**Question 1:**
[22,27,16,2,18,6] -> Selection Sort

1-) Write all sorting process (Selection Sort) step by step.

2-) Time Complexity: Which case type provides after array has sorted?
    a-Average Case
    b-Worst Case
    c- Best Case

**Answer 1:**

[22,27,16,2,18,6] 
1. Algorithm search to lowest number (2)
2. Algorithm pull (2) into (22)
3. Algorithm search to lowest number (without array's 0. index. It's already lowest) *New array: [2,27,16,22,18,6]*
4. Algorithm pull (6) into (27)
5. Algorithm search to lower number (without array's 0. and 1st. First two index already sorted) *New array: [2,6,16,22,18,27]*
6. Algorithm pull (16) into (16). Because 16 is 3rd lowest number in this array. *New array: [2,6,16,22,18,27]*
7. Algorithm search to lower number (without array's 0, 1st and 2nd. First three index already sorted)
8. Algorithm pull (18) into (22). *New array: [2,6,16,18,22,27]*
9. Algorithm search to lower number (without array's 0, 1st, 2nd and 3rd. First four index already sorted)
10. Algorithm pull (22) into (22). Because 22 is 5th lowest number in this array. *New array: [2,6,16,18,22,27]*
11. Sorting process done.
___

**Question 2:** [7,3,5,8,2,9,4,15,6]-> Selection Sort

1-) Write first 4 process on Selection Sort.

**Answer 1:**

   1. Algorithm search to lowest number (2)
   2. Algorithm pull (2) into (7) *New array: [2,3,5,8,7,9,4,15,6]*
   3. Algorithm search to lowest number (3)
   4. Algorithm pull (3) into (3) *New array: [2,3,5,8,7,9,4,15,6]*
