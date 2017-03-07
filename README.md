# My Interview Preparation Studies

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 1) STRINGS AND ARRAYS

### 1.1 - Is Unique
Implement an algorithm to determine if a string has all unique characters. What if you cannot use additional data structures?

### 1.2 - Check Permutation
Given two strings, write a method to decide if one is a permutation of the other.

### 1.3 - URLify
Write a method to replace all spaces in a string with ‘%20’. You may assume that the string has sufficient space at the end to hold the additional characters, and that you are given the “true” length of the string. (Note: implementing in Java, please use a character array so that you can perform this operation in place.) 

### 1.4 - Palindrome Permutation
Given a string, write a function to thick if it is a permutation of a palindrome. A palindrome is a word of phrase that is the same forwards and backwards. A permutation is a rearrangement of letters. The palindrome does not need to be limited to just dictionary words.

### 1.5 - One Away
There are three types of edits that can be performed on strings: insert a character, remove a character or replace a character. Given to strings, write a function to check if they are one edit or zero edits away.

### 1.6 - String Compression
Implement a method to perform basic string compression using the counts of repeated characters. For example, the string aabbccccaaa would become a2b1c5a3. If the compressed string would not become smaller than the original string, your method should return the original string. You can assume the string has only uppercase and lowercase letters (a-z)

### 1.7 - Rotate Matrix
Given an image represented by an NxN matrix, where each pixel in the image is 4 bytes, write a method to rotate the image by 90 degrees. Can you do this in place?

### 1.8 - Zero Matrix
Write an algorithm such that if an element in an MxN matrix is 0, its entire row and column are set to 0.

### 1.9 - String Rotation
Assume you have a method isSubstring which checks if one word is a substring of another. Given two strings, s1 and s2, write code to check if s2 is a rotation of s1 using only one call to isSubstring. (e.g. “waterbottle” is a rotation of “erbottlewat”)

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 2) LINKED LISTS

### 2.1 - Remove Dups
Write code to remove duplicates from an unsorted linked list.
Follow up - How would you solve this problem if a temporary buffer is not allowed?

### 2.2 - Return Kth to the last
Implement an algorithm to find the Kth to the last element of a singly linked list.

### 2.3 - Delete middle node
Implement and algorithm to delete a node in the middle (i.e., any node but the first and last node, not necessarily the exact middle) of a singly linked list, given only access to the node.

EXAMPLE:
Input: the node c from the linked list a->b->c->d->e->f
Result: nothing is returned but the new linked list looks like a->b->d->e->f

### 2.4 - Partition
Write code to partition a linked list around a value X, such that all nodes less than X come before all nodes greater than or equal to X. If X is contained within the list, the values of X only need to be after the elements less than X (see below). The partition element X can appear anywhere in the “right partition”; it doesn’t need to appear between the left and right partitions.

EXAMPLE:
Input: 3 -> 5 -> 8 -> 5 -> 10 -> 2 -> 1 [partition = 5]
Output: 3 -> 1 -> 2 -> 10 -> 5 -> 5 -> -> 8

### 2.5 - Sum lists
You have two numbers represented by a linked list, where each node contains a single digit. The digits are stored in reverse order, such that the 1’s digit is at the head of the list. Write a function that adds the two numbers and returns the sum as a linked list.

EXAMPLE:
Input: (7 -> 1 -> 6) + (5 -> 9 -> 2). That is, 617 +295.
Output: 2 -> 1 -> 9. That is, 912.

FOLLOW UP
Suppose the digits are stored in a forward order. Repeat the above problem.
Input: (6 -> 1 -> 7) + (2 -> 9 -> 5). That is, 617 +295.
Output: 9 -> 1 -> 2. That is, 912.

### 2.6 - Palindrome
Implement a function to check if a linked list is a palindrome.

### 2.7 - Intersection
Given two singly linked lists, determine if the two lists intersect. Return the intersecting node. Note that the intersection is defined based on reference, not value. That is, if the nth node of the first linked list is the exact same node (by reference) as the nth node of the second linked list, then they are intersecting.

### 2.8 - Loop Detection
Given a circular linked list, implement an algorithm that returns the node at the beginning of the loop. 

DEFINITION
Circular linked list: A (corrupt) linked list in which a node’s next pointer points to an earlier node, so as to make a loop in the linked list

EXAMPLE
Input: a -> b -> c -> d -> e -> c (the same c as earlier)
Output: c

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 3) Stacks and Queues

### 3.1 - Three in One
Describe how you could use a single array to implement three stacks.

### 3.2 - Stack Min
How would you design a stack which, in addition to push and pop, has a function which returns the minimum element? Push, pop and min should all operate in O(1) time.

### 3.3 - Stack of Plates
Imagine a literal stack of plates. If the stack gets too high, it might topple. Therefore, in real life, we would likely start a new stack when the previous stack exceeds som threshold. Implement a data structure SetOfStacks that mimics this. SetOfStacks should be composed of several stacks and should create a new stack once the previous one exceeds capacity. SetOfStacks.push() and SetOfStacks.pop() should behave indentically to a sinfle stack (that is, pop() should return the same calues as it would if there were just a single stack).

FOLLOW UP:
Implement a function popAt(int index) which performs a pop operation on a specific sub-stack.

### 3.4 - Queue via Stacks
Implement a MyQueue class which implements a queue using two stacks.

### 3.5 - Sort Stack
Write a program to sort a stack such that the smallest items are on the top. You can use an additional temporary stack, but you may not copy the elements into any other data structure (such as an array). The stack suports the following operations: push, pop, peek, and isEmpty.

### 3.6 - Animal Shelter
An animal shelter, which holds only dogs and cats, operates on a strictly "first in, first out" basis. People must adopt either the "oldest" (based on arrival time) of all the animals at the shelter, or they can select whether they would prefer a dog or a cat (and will receive the oldest animal of that type). They cannost select which specific animal they would like. Create the data astructures to maintain this system and implement operations such as enqueue, dewueueAny, dequeueDog, and dequeueCat. You may use the built-in LinkedLust data structure. 

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 4) Trees and Graphs

### 4.1 - Route between nodes
Given a directed graph, design an algorithm to find out whether there is a route between two nodes.

### 4.2 - Minimal Tree
Given a sorted (increasing order) array with unique integer elements, write an algorithm to create a binary search tree with minimal height.

### 4.3 - List of Depths
Given a binary tree, design an algorithm which creates a linked list of all the nodes at each depth (e.g., if you have a tree with depth D, you'll have D linked lists)

### 4.4 - Check Balanced
Implement a function to check if a binary tree is balanced. For the purposes of this question, a balanced tree is defined to ba a stree such that the heights of the two subtrees of any node never differ by more than one. 


### 4.5 - Validate BST
Implement a function to check if a binary tree is a binary search tree.


### 4.6 - Successor
Write an algorithm to find the "next" node (i.e., in-order successor) of a given node in a binary search tree. You may assume that each node has a link to its parents. 


### 4.7 - Build order
You are given a list of projects and a list of dependencies (which is a list of pairs of projects, where the second project is dependent on the first project). All of a project's dependeies must be built before the project is. Find a build order that will allow the projects to be built. If there is no valid build order, return an error.

EXAMPLE:

Input:
projects: a, b, c, d, e, f
dependencies: (a,d), (f,b), (b,d), (f,a), (d,c)

Output: 
f, e, a, b, d, c


### 4.8 - First Common Ancestor
Design an algorithm and write code to find the first common ancestor of two nodes in a binary tree. Avoid storing additionall nodes in a data structure. NOTE: This is not necessarily a binary search tree.


### 4.9 - BST sequences
A binary search tree was created bu traversing through an array from left to right and inserting each element. Given a binary search tree with distinct elements, print all possible arrays that coule have led to this tree.

EXAMPLE:    
   2    
  / \    
1   3    
 
Output:
[2,1,3], [2.3.1]

### 4.10 - Check Subtree
T1 and T2 are two very large binary trees, with T1 much bigger than T2. Create an algorithm to determine if T2 is a subtree of T1. A tree T2 is a subtree of T1 if there exists a node n in T1 such that the subtree of n is identical to T2. That is, if you cut off the tree at node n, the two trees wuold be identical.


### 4.11 - Random Node
You are implementing a binary tree class from scratch which, in addition to insert, find and delete, has a method getRandomeNode() which returns a randome node from the tree. All nodes should be equally likely to be chosen. Design and implement an algorithm to getRandomNode, and explain how you would implement the rest of the methods.


### 4.12 - Paths with Sum
You are given a binary tree in which each node contains an integer value (which might be positive or negative). Design an algorithm to count the number of paths that sum to a given value. The path does not need to start or end at the root or a leaf, but it must go downwards (traveling only from parent nodes to child nodes).


*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 5) Bit Manipulation

Bitwise operators treat their operands as a sequence of 32 bits (zeroes and ones), rather than as decimal, hexadecimal, or octal numbers. For example, the decimal number nine has a binary representation of 1001. Bitwise operators perform their operations on such binary representations, but they return standard JavaScript numerical values.    

The following table summarizes JavaScript's bitwise operators:    

| Operator | Usage | Description |
|------------------------------|---------|----------------------------------------------------------------------------------------------------------------------------------|
| Bitwise AND | a & b | Returns a one in each bit position for which the corresponding bits of both operands are ones. |
| Bitwise OR | a &#124; b | Returns a one in each bit position for which the corresponding bits of either or both operands are ones. |
| Bitwise XOR | a ^ b | Returns a one in each bit position for which the corresponding bits of either but not both operands are ones. |
| Bitwise NOT | ~ a | Inverts the bits of its operand. |
| Left Shift | a << b | Shifts a in binary representation b (< 32) bits to the left, shifting in zeroes from the right. |
| Sign-propogating right shift | a >> b | Shifts a in binary representation b (< 32) bits to the right, discarding bits shifted off. |
| Zero-fill right shift | a >>> b | Shifts a in binary representation b (< 32) bits to the right, discarding bits shifted off, and shifting in zeroes from the left. |

### 5.1 - Insertion
You are given two 32-bit numbers, N and M, and two bit positions, i and j. Write a method to insert M into N such that M starts at bit j and ends at bit i. You can assume that the bits j through i have enough space to fit all of M. That is, if M=10011, you can assume that there are atleast 5 bits between j and i. You would not, for example, have j=3 and i=2, because M could not fully fit between bit 3 and bit 2.

### 5.2 - Binary to string
Given a real number between 0 and 1 (e.g., 0.72) that is passed in as a double, print the binary representation. If the number cannot be represented accurately in binary with at most 32 characters, print "ERROR"

### 5.3 - Flip Bit to Win
You have an integer and you can flip exactly one bit from a 0 to a 1. Write code to find the length of the longest sequence of 1s you could create.

EXAMPLE:

Input: 1175 (or: 11011101111)
Output: 8

### 5.4 - Next Number
Given a positive integer, print the next smallest and the next largest number that have the same number of 1 bits in their binary representation.

### 5.5 - Debugger
Explain what the following code does: ((n & (n-1)) == 0)

### 5.6 - Conversion
Write a function to determine the number of bits you would need to flip to convert integer A to integer B.

EXAMPLE:
Input: 29 (or: 11101), 15 (or: 01111)
Output: 2

### 5.7 - Pairwise Swap
Write a program to swap odd and even bits in an integer with as few instructions as possible (e.g., bit 0 and bit 1 are swapped, bit 2 and bit 3 are swapped, and so on).

### 5.8 - Draw Line
A monochrome screen is stored as a single array of bytes, allowing eight consecutive pixels to be stored in one byte. The screen has width w, where w is divisible by 8 (that is, no byte will be split accress rows). The height of the screen, of course, can be rerived from the length of the array and the width. Implement a function that draws a horizontal line from (x1, y) to (x2, y). The method signature should look something like this:    
drawLine(byte[] screen, int width, int x1, int x2, int y)

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 6) Math and Logic Puzzles


### 6.1 - The Heavy Pill
You have 20 bottles of pills, 19 bottles have 1.0 gram pills, but one has pills of weight 1.1 grams. Given a scale that provides an exact measurement, how would you find the heavy bottle? You can only use the scale once.

### 6.2 - Basketball
You have a basketball hoop and someone says that you can play one of two games.    
Game 1: You get one shot to make the hoop.    
Game 2: You get three shots and you have to make two of three shots.    
If p is the probability of making a particular shot, for which values of p should you pick one game or the other?

### 6.3 - Dominos
There is an 8x8 chessboard in which two diagonally opposite corners have been cut off. You are given 31 dominos, and a single domino can cover exactly two squares. Can you use the 31 dominos to cover the entire board? Prove your answer (by providing an example or showing why it's impossible)

### 6.4 - Ants on a Triangle
There are three ants on different vertices of a triangle. What is the probability of collision (between any two or all of them) if they start walking on the sides of the triangle? Assume that each ant randomly picks a direction, with either direction being equally likely to be chosen, and that they walk at the same speed.    
Similarly, find the probability of collision with n ants on an n-vertex polygon.

### 6.5 - Jugs of Water
You have a five-quart jug, a three-quart jug, and an unlimited supply of water (but no measuring cups). How would you come up with exactly four quarts of water? Note that the jugs are oddly shaped, such that filling up exactly "half" of the jug would be impossible.

### 6.6 - Blue-Eyed Island
A bunch of people are living on an island, when a visitor comes with a strange order: all blue-eyed people must leave the island as soon as possible. There will be a flight out at 8:00pm every evening. Each person can see everyone else's eye color, but they don't know their own (nor is anyone allowed to tell them). Additionally, they do not know how many people have blue eyes, although they do know that at least one person does. How many days will it take the blue-eyed people to leave?

### 6.7 - The Apocalypse
In the new post-apocalyptic world, the world queen is desperately concerned about the birth rate. Therefore, she decrees that all families should ensure that they have one girl or else they face massive fines. If all families abide by this policy - that is they have continue to have children until they have one girl, at which point they immediately stop - what will the gender ratio of the new generation be? (Assume that the odds of someone having a boy or a girl on any given pregnancy is equal.) Solve this out logically and then write a computer simulation of it.

### 6.8 - The Egg Drop Problem
There is a building of 100 floors. If an egg drops from the Nth floor or above, it will break. If it's dropped from any floor below, it will not break. You're given two eggs, Find N, while minimizing the number of drops for the worst case.

### 6.9 - 100 Lockers
There are 100 closed lockers in a hallway. A man begins by opening all 100 lockers. Next, he closes every second locker. Then, on his third pass, he toggles every third locker (closes it if it is open or opens if it is closed). This process continues for 100 passes, such that on each pass i, the man toggles every ith locker. After his 100th pass in the hallway, in which he toggles only locker #100, how many lockers are open?

### 6.10 - Poison
You have 100 bottles of soda, and exactly one is poisoned. You have 10 test strips which can be used to detect poison. A single drop of poison will turn the test trip positive permanently. You can put any number of drops on a test strip at once and you can resuse a test strip as many times as you'd like (as long as the results are negative). However, you can only run tests once per day and it takes seven days to return a result. How would you figure out the posoned bottle in as few days as possible?    
FOLLOW UP:
Write code to simulate your approach.

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 7) Object-Oriented Design

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 8) Recursion and Dynamic Programming

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 9) System Design and Scalability

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 10) Sorting and Searching

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 11) Testing

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 12) C and C++

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 13) Java

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 14) Databases

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 15) Threads and Locks

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 16) Moderate

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************

## 17) Hard

*****************************************************************************************************************************************************************************************************************************************************************************************************************************************
