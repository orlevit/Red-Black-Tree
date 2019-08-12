# Red-Black-Tree

In this project online algorithm is designed(Online space) for the next problem, written in C language:\
  - Input : An array of numbers of length ݊n and number k݇\
  - Output: A list of the k smallest elements in the array in ascending order.
 
_Algorithm_ : using a red-black tree that stores k elements.\
&nbsp;&nbsp;insert element into a red-black tree takes teta of log k, if the new elements is smaller\
              than the bigest one in the tree(and the tree contains k elements) than do delete first in\
              a cost of teta of log k and then insert = in total: teta of log k.\
              print the min elements by order is done by inorder traversal in cost of teta of k.\
              space complexity: in any given moment only the k (at most) elements in the red_black\
              tree are saved.
