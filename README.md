# Date Night


## Learning Goals
- Practice breaking a program into logical components
- Distinguishing between classes and instances of those classes
- Understanding how binary search trees work to store and find data
- Testing components in isolation and in combination
- Use and implement iteration or recursion techniques
- Measure test coverage with SimpleCov
## Overview
You are a junior developer at Netflix. You’re on a team that is developing a list of movies for Netflix users called “Suggested for You.” Each time movies are added to Netflix, an algorithm determines a score of how likely a given user is to enjoy that movie.

- Scores are integers between 0 and 100
- No two movies will get the same score

It is your job to take new movies that have been scored, and store them in a Binary Search Tree.

## Binary Search Trees
A binary search tree is a fundamental data structure useful for organizing large sets of data. It’s ideal whenever you need to retrieve and sort data quickly.

More on Wikipedia: http://en.wikipedia.org/wiki/Binary_search_tree

A binary tree is built from nodes. Each node has:

A) An element of data
B) A link to the left. All nodes to the left have elements with a value less or lower than this node’s data element.
C) A link to the right. All nodes to the right have elements with a value more or greater than this node’s data element.
