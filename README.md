# Machine-Learning-Tutorial

# Sharing my Machine Learning Journey
Semester 5 Aug-Dec 24

NewBie Here On 1 Sep24'
------------------------------------
Day 1: Some Youtube Video's Summary

1. Do a linear regression model based project (eg : predicting grades of a student)

2. A clustering algorithm project(eg : use k nearest means to predict the safety of a  car)

3. Make a project to classify a cancer cell as benign or malignant.

4. use a neural network to classify digits of MNIST dataset.

Link 1: https://www.datacamp.com/blog/machine-learning-projects-for-all-levels
------------------------------------
Day2 : HBD 

Day 3: No major research watched random videos and explored them 

MACHINE LEARNING 
1. campus x yt channel -nitish sir http://youtube.com/@campusx-official 
2. coursera machine learning from Stanford University
3.https://andrewng.org/courses/
4. book http://deeplearningbook.org 
5. learn basic maths, algebra and probability
6. Stanford lectures present on youtube.(CS229 for machine learning, CS224 for NLP)
7. Krish Naik ON yt
8. Lazy Programmers courses
9.Codebasics
   Statquest
    CampusX
      Sentdex
10 Codebasics
Statquest
CampusX
Sentdex
11. MIT Introduxtion to ML
12. Balaji Srinivasan
13. https://gordicaleksa.medium.com/get-started-with-ai-and-machine-learning-in-3-months-5236d5e0f230
14. Course era link https://www.deeplearning.ai/
Note
Read things from books, or if you are going to use video lectures, watch andrew ng and at the same time try to refer to books. It will take time when you will learn from books, but the level of understanding will be better as compared to video lectures



http://DeepLearning.AI Specialization by Andrew Ng (http://deeplearning.ai/courses/deep-l…) 

 * http://Fast.ai Practical Deep Learning for Coders (http://course.fast.ai)
-------------------------------------------------------
5 Sep  Tired as Hell




-------------------------------------------------------

12 SEP UPDATE
Learning AIML with python Harward course by FreeCode Camp


------------------------------------------------------
13 September 
BFS and DFS in the Maze Puzzle and 15-Puzzle Game:

BFS (Breadth-First Search) and DFS (Depth-First Search) are basic search algorithms used to explore all possible paths in a puzzle.
However, they are not optimal because they do not necessarily find the shortest or best solution.
BFS explores all nodes level by level, while DFS explores one branch completely before backtracking, which may lead to unnecessary exploration of inefficient paths.
Greedy BFS:

Greedy BFS improves over BFS and DFS by introducing a heuristic function to guide the search.
In the context of the maze puzzle, we can use Manhattan distance as the heuristic.
Manhattan distance is the distance between the current position and the goal, measured by the number of horizontal and vertical moves, without considering obstacles.
By using this heuristic, we make decisions that bring us closer to the destination more efficiently, leading to a more optimal traversal compared to standard BFS and DFS.
A Algorithm:*

While Greedy BFS focuses only on the heuristic (how close we are to the goal), it can still miss the shortest path because it doesn't account for the steps taken so far.
The A algorithm* improves upon this by combining the heuristic (e.g., Manhattan distance) with the actual cost (number of steps) taken to reach the current position.
In A*, we calculate the total cost as:
Total cost
=
Steps taken so far
+
Heuristic (Manhattan distance)
Total cost=Steps taken so far+Heuristic (Manhattan distance)
This ensures that we consider both the proximity to the destination and the path taken, making A* more reliable and optimal for finding the shortest path.
