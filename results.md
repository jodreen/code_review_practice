The three functions we decided to analyze are:
1. reshape
2. get_increment
3. mean

Comments on Jordeen's Code:

Comments on Lisa's Code:

Comments on Alon's Code:

"reshape" is as good as it can be.

"get_increment" didn't need an if/else clause but it works.
Code performance wouldn't be affected by that, but brevity could have been improved.

"mean" is clean, short, and fast since it makes use of an iterator.
Nothing unnecessary is run.


Comments on Ying's Code:
  1. reshape:
    - Nicely done. Brief, efficient, clear, and correct.
  2. get_increment:
    - range(0, dim) could be written as range(dim)
    - recommmend replacing for loop with list comprehension
    - Code is efficient and clear
  3. mean:
    - defining mean_along_axis is unnecessary, simply return it
      value immediatly 
    - code is efficient