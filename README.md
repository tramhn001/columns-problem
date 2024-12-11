# columns-problem
Problem to be completed during Industry Prep - Interview Prep

## Problem Statement 
The input to your function will be a tuple of tuples. For example:

```
((5, 6, 7, 8),
 (3, 9, 2, 5),
 (2, 1, 9, 2))
```

Your function should return the index of the column with the highest sum.

### Examples:

```
matrix_1 = ((5, 6, 7, 8),
            (3, 9, 2, 5),
            (2, 1, 9, 2))
top_column(matrix_1) => 2
```

Explanation: Column 2 has a sum of 18, higher than any other column.

```
matrix_2 = ((1, 2),
            (3, 4))
top_column(matrix_2) => 1
```

```
matrix_3 = ((3,),
            (4,),
            (9,))
top_column(matrix_3) => 0
```

```
matrix_4 = ((-2, -1, -3),)
top_column(matrix_4) => 1
```