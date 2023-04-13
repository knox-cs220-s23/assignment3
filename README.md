# Assignment 3
## Tree coding challenge
For each of the questions below, make sure that you clearly describe any assumptions you make. All code should be well commented. You may not import any data structures, but you may use classes and arrays. Your code should be generic where possible. If you need additional data structures, implement them yourself. For example, Question 1.2 would benefit greatly from the existence of a linked list class.

You may have written some of these classes and functions before but you should be able to do all of this with minimal javadoc reference.

1. Design and implement a tree data structure.  Ensure the tree has a `toString()` method which produces a legible representation of the tree. You will use this data structure for the remaining questions in this assignment, so read those first. Your class should be as general as possible - this means you can use it to solve problems that are not asked below. Implement the following methods for your tree. Make sure to write detailed comments explaining any design decisions you make. For each of these functions, report the time and space complexity of your implementation.
	1. `depth` should return the maximum depth of your tree (ie the node with the longest path back to the root). If implemented correctly, this method should be callable at any node in the tree.
	2. `pathToRoot` should take in a node that exists in your tree and return the sequence of nodes from the root to that node. 
	3. `siblings` should take in a node and return all other nodes which are children of said node’s parent.
	4. `LeastCommonSubsumer`should take in two nodes and return the deepest node which is a parent to both of them.
2. Describe/draw instances of trees. You should use as many trees as you need to demonstrate that your data structure is capable of representing any of the trees you will need to represent for the remaining questions. Demonstrate instantiating these trees in code.
3. In a separate class, Implement a pre-order, in-order, and post-order traversal of your tree. Write a main method in this class to print the nodes in the order that they are evaluated in each of the traversals. Use the examples from question 2. Describe the traversals in detail in your writeup.
4. Implement in-order traversal in O(1) space and O(n) time. Recall that the recursive solution is O(n) space. Describe your algorithm in detail in the writeup.
5. Write a static method that determines whether a tree with integer values at its nodes is a sum tree or not. That is, the integer at each node in the tree should be equal to the sum of all of its children.
