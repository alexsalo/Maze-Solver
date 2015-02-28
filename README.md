# Maze-Solver
Input:
  * closed-borders solvable maze

Example:
~~~java
+--+--+--+--+--+--+--+--+--+--+
|             S|     |     |  |
+  +--+--+--+  +--+  +  +  +  +
|     |  |     |     |  |  |  |
+--+  +  +  +--+  +--+--+  +  +
|     |  |        |     |     |
+  +--+  +--+--+--+  +  +  +--+
|     |        |     |        |
+--+  +--+  +  +  +--+--+--+  +
|  |  |  |  |     |           |
+  +  +  +  +--+--+  +--+--+--+
|           |     |        |  |
+--+  +--+--+  +--+--+--+  +  +
|     |        |     |     |  |
+  +--+  +--+  +  +--+  +--+  +
|  |     |  |  |     |      F |
+  +  +--+  +  +--+  +--+--+  +
|  |  |     |     |  |     |  |
+  +  +  +--+--+  +  +  +--+  +
|     |              |        |
+--+--+--+--+--+--+--+--+--+--+
~~~

Output:
  * List of directions to get from S to F. 
  * lllllllllllllddrrrddlllddrrrddddlluulddrrrddlllddddddrrrruuuurrruurrrrrddddrrrddlllllllluurrruulddlllddrrrrrrrrrrrrruuuullluurrrllllddrrrddddlluullluuuuuurrrllllddllllllddlllddddlluuuuuurrruurrrrrruuuurrddrrrruurrruurrddrrrrrrddlllllllllddrrrrrrddlllddrrrrrl
 
In the process, program prints the maze after each iteration so you can see the movement (nice to watch in debug mode)
