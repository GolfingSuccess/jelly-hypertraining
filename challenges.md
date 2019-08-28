<!-- NOTE: Code is indented with two spaces, DO NOT remove them! It will break the GitHub Pages rendered output. Those spaces do not appear there, and you're not intended to read the file from here. ;) -->

# List of easy-to-medium challenges you can try

The bytecount is the minimum bytecount users in this class have been able to get to, but you should feel free to outgolf or notice a new feature that lets you golf any one of these further. If you do, please ping a teacher or submit a pull request so that the bytecount can be updated. Here is a list with challenges:

+ Add two numbers (e.g. f(1, 2)=3) *Minimum needed bytes: 1*
+ Subtract two numbers (e.g. f(5, 3)=2) *Minimum needed bytes: 1*
+ Multiply two numbers (e.g. f(2, 4)=8) *Minimum needed bytes: 1*
+ Divide two numbers (e.g. f(3, 2)=1.5) *Minimum needed bytes: 1*
+ Integer-divide two numbers (e.g. f(9, 4)=2) *Minimum needed bytes: 1*
+ Modulo two numbers (e.g. f(100, 57)=43) *Minimum needed bytes: 1*
+ Exponentiate two numbers (e.g. f(6, 6)=46656) *Minimum needed bytes: 1*
+ N-root two numbers (e.g. f(134217728, 9)=8) *Minimum needed bytes: 3*
+ Negate a number (e.g. f(600)=-600, f(-5)=5) *Minimum needed bytes: 1*
+ Find the absolute value (e.g. f(-8192)=8192, f(11)=11) *Minimum needed bytes: 1*
+ Find Nth prime number (e.g. f(15)=47) *Minimum needed bytes: 2*
+ Find Nth Fibonacci number (e.g. f(100)=354224848179261915075) *Minimum needed bytes: 2*
+ Create an N×M 2D array (list of lists) of anything. Even inconsistent values are allowed. Example for f(5, 4):
```
  [[1, 3, 1, 4, 8888], [[1, 2], 3, '@', 0, -9999999999999], ['', '', 1j, (1+2j), ['l', 'l', 'a', 'm', 'a']], [1, 2, 3, 4, 5]]
```
*(Minimum needed bytes: 2)*
+ Reverse a list (e.g. f([1, 2, 'a', ['b', 'c']])=[['b', 'c'], 'a', 2, 1]) *Minimum needed bytes: 1*
+ Find 1/N (e.g. f(5)=0.2) *Minimum needed bytes: 1*
+ Given a prime number N, find the prime after N (e.g. f(47)=53) *Minimum needed bytes: 2*
+ Find the largest list of consecutive positive integers that sum to N (e.g. f(100)=[9, 10, 11, 12, 13, 14, 15, 16]) *Minimum needed bytes: 5*
+ Same as above, but in compact form [min, max] or [max, min], even if min == max. (e.g. f(100)=[9, 16]) *Minimum needed bytes: 7*
+ Draw a diagonal line from top-left to bottom-right, using space as padding and a consistent non-whitespace char as the line. Example for f(10):
```
  \
   \
    \
     \
      \
       \
        \
         \
          \
           \
```
*(Minimum needed bytes: 5)*
+ Draw an X with odd-length diagonals, using space as padding and a consistent non-whitespace char as the X. You won't have to handle even lengths. Example for f(7):
```
  X     X
   X   X
    X X
     X
    X X
   X   X
  X     X
```
*(Minimum needed bytes: 8)*
+ Draw an N×N checkerboard with white top-left square. Use space for white and a consistent non-whitespace char for black. Trailing spaces not required. Example for f(8):
```
   # # # #
  # # # #
   # # # #
  # # # #
   # # # #
  # # # #
   # # # #
  # # # #
```
*(Minimum needed bytes: 7)*
+ Same as above, but with black top-left square instead. Example for f(8):
```
  # # # # 
   # # # #
  # # # # 
   # # # #
  # # # # 
   # # # #
  # # # # 
   # # # #
```
*(Minimum needed bytes: 7)*
+ Draw a right triangle with equal perpendicular sides of length N. You must use a not necessarily consistent non-whitespace char. Example for f(5):
```
  #
  ##
  ###
  ####
  #####
  ####
  ###
  ##
  #
```
*(Minimum needed bytes: 4)*
+ Draw a square with side length N (not necessarily consistent non-whitespace char). Example for f(9):
```
  #########
  #########
  #########
  #########
  #########
  #########
  #########
  #########
  #########
```
*(Minimum needed bytes: 4)*
+ Draw a rectangle with side lengths N×M (not necessarily consistent non-whitespace char). Example for f(4, 3):
```
  ####
  ####
  ####
```
*(Minimum needed bytes: 3)*
+ Find the average (e.g. f([1.5, 2.33, 3.1010101, 3.14])=2.517752525) *Minimum needed bytes: 2*
+ Find the median (e.g. f([-0.1777777777, -2.5, -333333, -444])=-223.25) *Minimum needed bytes: 2*
+ Find the average of the average and median (e.g. f([1, 10, 20, 30])=15.125) *Minimum needed bytes: 6*
+ Find the LCM of a list of integers (e.g. f([4, 8, 12])=24) *Minimum needed bytes: 3*
+ Find the GCD of a list of integers (e.g. f([6, 120])=6) *Minimum needed bytes: 2*
+ Simplify a fraction of the form [x, y] (e.g. f([6, 8])=[3, 4]) *Minimum needed bytes: 3*
  + Alternatively, you may take two arguments x and y (e.g. f(6, 8)=[3, 4]) *Minimum needed bytes: 3*
+ Execute Jelly code (e.g. f(['1', '+', '1'])=2) *Minimum needed bytes: 1*
+ Determine why these can be done in 0 bytes:
  + Evaluate a valid Python literal and listify it (e.g. f(['1',','])=[1])
  + Execute valid Python code (e.g. f(['a', '='. '1', ';', 'p', 'r', 'i', 'n', 't', '(', 'a', '+', '1', ')'])=[] plus `2\n` on STDOUT)
+ Explain why this happens:
  + `4+×¥80¤` results in `324`.
