Add your answers to the Algorithms exercises here.

A.) Depending on n this could b an infinite loop, loop once, or not loop at all

- if n == 1, this loop will run exactly once, then stop.
- If n > 1, this will run infinitely.
- if n < 1 it will not run at all.

**n^2 will never be greater than n^3, unless n is negative, or 0**

B.) this code has a complexity of O(n \* logn^2).
The outer most loop has complexity O(n), with the 2 next loops having logn complexity. getting faster as we get further in iterations. The inner most loop just runs constant 10x each time it is run

C.) this is a linear recursive function O(n)
