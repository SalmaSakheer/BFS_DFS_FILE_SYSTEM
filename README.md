File System Representation and Search Using BFS and DFS

Activity Details

- Activity ID: SY-S3-B-09
- Subject: Data Structures and Algorithms
- Programming Language: C

Objective

To represent a file system as a graph using an adjacency matrix and search folders using Breadth-First Search (BFS) and Depth-First Search (DFS).

Description

In this project, each folder is represented as a node, and connections between folders are represented as edges. An adjacency matrix is used to store these connections.

Algorithms Used

- BFS (Breadth-First Search): Visits connected folders level by level using a queue.
- DFS (Depth-First Search): Explores one path as far as possible before returning to another path.

Sample Input

5
0 1 1 0 0
1 0 0 1 0
1 0 0 0 1
0 1 0 0 0
0 0 1 0 0
0
4

Sample Output

BFS Traversal: A B C D E
DFS Traversal: A B D C E
BFS Traversal: A B C D E
Target folder E is reachable.

Conclusion

This project demonstrates graph representation using an adjacency matrix and the use of BFS and DFS algorithms to traverse folders and check reachability.
