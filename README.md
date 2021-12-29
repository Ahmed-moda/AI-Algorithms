1. In this project, you are expected to solve a 2-D maze using DFS. A maze is path typically from start node ‘S’ to Goal node ‘E’.
Input: 2D maze represented as a string.
Output: the full path from Start node to End node (Goal Node), direct path to go from Start to End directly.
Example: let’s say the end node is 6 in case of DFS.
Full Path: 1, 2, 5, 9, 10, 6.
Path: 1, 2, 6.
The input and output are explained below. Your code should be generic for any dimension of a given maze.
Maze: 'S,.,.,#,.,.,. .,#,.,.,.,#,. .,#,.,.,.,.,. .,.,#,#,.,.,. #,.,#,E,.,#,.' •
Maze is a string, rows are separated by space and columns are separated by comma ‘,’. • 
The board is read row wise, the nodes are numbered 0-based starting the leftmost node. • 
You have to create your own board as a 2D array (NO 1D ARRAY ALLOWED) of Nodes.
Algorithm (2)
2. Implement Connect 3 using Alpha Beta algorithm, this game is played on a vertical board which has 8 columns and 5 rows. 
Each column has a hole in the upper part of the board, where pieces are introduced. 
There is a window for every square, so that pieces can be seen from both sides.
Both players have a set of 20 thin pieces (like coins); each of them uses a different color. 
The board is empty at the start of the game. GUI is already implement, you need to implement only Alpha beta function.
3. Implement K-Means algorithm on a dataset that holds a diagnosis for the eyes of patients.
• The diagnosis is based on the following features:
  Age: (0) young, (1) adult.
  Prescription: (0) myope, (1) hypermetrope.
  Astigmatic: (0) no, (1) yes.
  Tear production rate: (0) normal, (1) reduced.
• The output classes are:
  Need contact lenses (1): the patient should be fitted with a special type of contact lenses.
  No contact lenses (0): the patient should not be fitted with a
  Special type of contact lenses.
• Dataset Sample:
• The Number of max iterations = 100
• Instead of using random centroids use the first k items from the training set
• Calculate the distance once using Manhattan and once using EuclideanEuclidean: Take the square root of the sum of the squares of the differences of the coordinates. o For example, if x = (a, b) and    y=(c, d) , the Euclidean distance between x and y is
Manhattan: Take the sum of the absolute values of the differences of the coordinates. o For example, if x = (a, b) and y=(c, d) , the Euclidean distance between x and y is
The output should be the centroids of the classes using Euclidean and Manhattan distances.
