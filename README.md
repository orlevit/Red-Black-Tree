# Red-Black-Tree

In this project online algorithm is designed(Online space) for the next problem, written in C language:\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Input &nbsp;: An array of numbers of length ݊n and number k݇\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Output: A list of the k smallest elements in the array in ascending order.
 
_Algorithm_ : using a red-black tree that stores k elements.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;insert element into a red-black tree takes teta of log k, if the new elements is smaller\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;than the bigest one in the tree(and the tree contains k elements) than do delete first in\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a cost of teta of log k and then insert = in total: teta of log k.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print the min elements by order is done by inorder traversal in cost of teta of k.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;space complexity: in any given moment only the k (at most) elements in the red_black\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;tree are saved.


Files:
- Red-Black-Tree             - The code with comments(the arraysmn and k are defined within).
- Red-Black-Tree-Executable  - Executable of the code
