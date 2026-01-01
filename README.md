<h1 align="center">Warshall Algorithm</h1>

<p align="center">	
  <a href="https://github.com/Mohammad533643/Dentist_site/blob/main/LICENSE.md" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/github/license/Mohammad533643/Dentist_site?color=informational" />
  </a>

  <img alt="Repo size" src="https://img.shields.io/github/repo-size/Mohammad533643/Warshall-Algorithm#?color=informational/">
</p>

<p>
  Warshall algorithm is used to determine all the existing paths between different vertices of a graph.<br>
  This program is mostly scientific in nature and suitable for students, and it may not be optimized enough in terms of time complexity, etc.
</p>

### Example

We have a graph with vertices A, B, C and edges AB, BC.<be>
We give the inputs to the program according to the code.

Input

```Bash

    Enter your set :A,B,C
    Enter the size of Relation : 2
    Enter Relation 1: AB
    Enter Relation 2: BC
```

Output

```Bash
w0 =  {('B', 'C'), ('A', 'B')}

w0:
[0, 1, 0]
[0, 0, 1]
[0, 0, 0]

w1:
[0, 1, 0]
[0, 0, 1]
[0, 0, 0]

w1 = {('B', 'C'), ('A', 'B')}

w2:
[0, 1, 1]
[0, 0, 1]
[0, 0, 0]

w2 = {('B', 'C'), ('A', 'C'), ('A', 'B')}

w3:
[0, 1, 1]
[0, 0, 1]
[0, 0, 0]

w3 = {('B', 'C'), ('A', 'C'), ('A', 'B')}
```

This indicates that, apart from the initial edges, there can be an edge from A to C.
