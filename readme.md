# Graph Algorithms in C

A menu-driven C program that reads a weighted graph from an adjacency 
matrix file and performs classic graph algorithms using a dynamic 
linked-list adjacency list representation.

## Algorithms Implemented
- Breadth-First Search (BFS)
- Depth-First Search (DFS)  
- Dijkstra's Shortest Path Algorithm

## Features
- Parses adjacency matrix from a .txt file into a linked-list structure
- Interactive menu-driven interface
- Dynamic memory allocation throughout
- Clean separation of graph construction and traversal logic

## How to Run
```bash
gcc -o graph main.c
./graph input.txt
```

## Concepts Demonstrated
- Graph theory and representation
- Recursive and iterative traversal
- Greedy shortest path logic
- Pointers, dynamic allocation, and linked lists in C
- File I/O
