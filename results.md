The three functions we decided to analyze are:
1. reshape
2. get_increment
3. mean

Comments on Jordeen's Code:
reshape
- code clarity: clear
- brevity: short
- code performance: fast, 592 ns per loop
get_increment
- code clarity:
- brevity: short
- code performance: 1.75 microsec per loop
mean
- code clarity: relatively clear, uses an intermediate variable
- brevity: longer
- code performance: uses built-in map 143 microseconds per loop

Comments on Lisa's Code:

Comments on Alon's Code:

"reshape" is as good as it can be.

"get_increment" didn't need an if/else clause but it works.
Code performance wouldn't be affected by that, but brevity could have been improved.

"mean" is clean, short, and fast since it makes use of an iterator.
Nothing unnecessary is run.


Comments on Ying's Code:
