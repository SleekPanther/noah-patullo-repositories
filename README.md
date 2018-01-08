# Noah Patullo's Repositories & Projects
A list of projects I've worked on  
[LinkedIn Profile](https://www.linkedin.com/in/NoahPatullo)

## Websites (web related)
- [PHP Magic Linking](https://github.com/SleekPanther/php-magic-linking)  
My own invention: a PHP template that simplifies linking to nested folders & automatically print the correct number of `../` before links
- [Merrill's Roxy Cinema](https://github.com/SleekPanther/roxy)  
Website Final project for database class (CS 148) focusing on the back end managing adding movies & updating showtimes for a generic movie theater
- [Invert Checkbox Selection (& deselect radio buttons)](https://github.com/SleekPanther/checkbox-toggle-selection)  
I created my own jQuery functions based on several examples because I wasn't happy with any existing solutions
- [UVM Bikes](https://github.com/SleekPanther/uvmbikes)  
Website Final Project for web design & css class (CS 142)
- [Pure CSS Dropdown](https://github.com/SleekPanther/css-dropdown)  
Adapted existing tutorial to create mobile-friendly responsive menu. (Most work is **not mine**, but I added comments to help myself & simplify some CSS)
- [Intro Web Design Final Project](https://github.com/SleekPanther/assignment5.0)  
Very simple site for a fake graphic design company. Not my proudest work now, but it was a start when I was learning

#### Team Projects (Repositories Contributed to)
- [Books 4 Equality repository](https://github.com/books4equality/books4equality) and [Live Site](http://www.books4equality.com/)  
Website for a Student-run club that lends out free textbooks to UVM students  
Site runs in Node.js but I mostly worked on the front-end

## Java
- [GPA Calculator](https://github.com/SleekPanther/gpa-calculator)  
A GPA calculator in JavaFX attempting to use the [**Model View Controller** (MVC) pattern](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)
- [Even or Odd Game](https://github.com/SleekPanther/even-odd-game)  
Replicated a simple Android app using JavaFX & skills I learned from CS 110 at UVM
- [Tetris Game](https://github.com/SleekPanther/tetris-java)  
Final Project for CS 110 at UVM
- [Set Game Valid Set Finder](https://github.com/SleekPanther/set-game)  
Algorithm to find valid sets in the [Game Set](https://en.wikipedia.org/wiki/Set_(game)) & potentiall provide hints. Iteratively implements n choose k for combinations & checks if any are a valid set.
- [Fibonacci Algorithms Runtime Comparison](https://github.com/SleekPanther/fibonacci-algorithms-comparison)  
Array Memoization, Recursive & Phi (Golden Ratio) formula
- [Prime Factorization (Java)](https://github.com/SleekPanther/prime-factor-java)  
Cobbled together various existing algorithms for finding Prime Factors. I did not design the algorithms, but focused on creating a way for users to interact more easily
- [Pascal's Triangle](https://github.com/SleekPanther/pascal)  
Used my knowledge of Java arrays to print out an arbitrary number of rows of Pascal's Triangle
- [Java Rounding Improved](https://github.com/SleekPanther/java-math-improved-round)  
A function that allows you to specify how many decimals to round to
- [Java Random() Improved](https://github.com/SleekPanther/java-math-improved-random)  
Several overloaded methods to allow you to specify an upper and lower bound for random numbers
- [Loop Performance (`i++` vs `++i`)](https://github.com/SleekPanther/loop-performance)  
Runtime comparison between post and pre increment
- **Algorithm Implementations**
  - **Graph Algorithms**
    - [Breadth First Search / Depth First Search](https://github.com/SleekPanther/breadth-first-search-depth-first-search-graphs)  
    Implementation of the common BFS & DFS algorithms
    - [Bipartite Graph Testing Algorithm](https://github.com/SleekPanther/bipartite-testing)  
    Modification of Breadth First Search to identify bipartite graphs
    - [Strong Connectivity](https://github.com/SleekPanther/graph-strong-connectivity)  
    Application of Breadth-First Search to see if a directed graph is Strongly Connected
    - [Topological Ordering](https://github.com/SleekPanther/topological-ordering)  
    Finds a Topological Ordering of vertices in a Directed Acyclic Graph
  - **Greedy**
    - [Interval Scheduling](https://github.com/SleekPanther/interval-scheduling)  
    Greedy Algorithm to find the maximum number of mutually compatible jobs
    - [Interval Partitioning](https://github.com/SleekPanther/interval-partitioning-greedy-algorithm)  
    Java Implementation of the greedy algorithm for the Interval Partitioning Problem
    - [Minimizing Lateness](https://github.com/SleekPanther/minimize-lateness)  
    Greedy Algorithm to minimize lateness when scheduling jobs on a processor
    - [Kruskal's Algorithm](https://github.com/SleekPanther/kruskals-algorithm-minimum-spanning-tree-mst)  
    Finds a Minimum Spanning Tree from a graph. Add lowest weight edges unless doing so causes a cycle.
    - [Reverse Delete Algorithm](https://github.com/SleekPanther/reverse-delete-algorithm)  
    Greedy Algorithm to find a minimum spanning tree in an undirected graph by deleting heaviest edges unless it would disconnect the graph
  - **Divide and Conquer**
    - [Counting Inversions](https://github.com/SleekPanther/counting-inversions)  
    Finds how similar 2 lists of rating are using the Divide and Conquer approach. Extension of MergeSort that actually displays the specific inversions as well as just counting the total number.
  - **Dynamic Programming**
    - [Weighted Interval Scheduling](https://github.com/SleekPanther/weighted-interval-scheduling)  
    The classic Dynamic Programming problem implemented in Java
    - [Knapsack Problem](https://github.com/SleekPanther/knapsack-problem)  
    Implementation of the classic 0-1 Integer Knapsack Problem
    - [Sequence Alignment](https://github.com/SleekPanther/sequence-alignment)  
    Find the minimum cost of aligning 2 sequences allowing gap insertion
    - [Bellman-Ford Algorithm](https://github.com/SleekPanther/bellman-ford)  
    Shortest Paths from every vertex to a goal vertex allowing negative-weight edges
  - **Flow Networks**
    - [Ford Fulkerson Max Flow Algorithm](https://github.com/SleekPanther/ford-fulkerson)  
    Finds max flow / min cut in a Flow Network. (Simple version, no capacity scaling)
    - [Bipartite Matching Algorithm](https://github.com/SleekPanther/bipartite-matching)  
    Extension of a Ford Fulkerson max flow problem to solve bipartite matching
    - [Circulation with Demands](https://github.com/SleekPanther/circulation-with-demands-network-flow)  
    Given a directed graph with edge capacities and vertex demands, is there a circulation of flow?
  - **NP-Complete Certifiers**
    - [3-SAT (Satisfiability) Certifier](https://github.com/SleekPanther/3-sat-certifier)  
    Polynomial-time certifier algorithm for the NP-Complete 3-SAT Problem
  - **Approximation Algorithms**
    - [Load Balancing Problem](https://github.com/SleekPanther/load-balancing-problem-approximation-algorithm)  
    Approximation Algorithm for the NP-Complete problem of balancing job loads on machines. Does not guarantee an optimal solution, but instead, a solution is within a factor of 1.5 of the optimal solution
    - [Minimum Weighted Vertex Cover (Pricing Method)](https://github.com/SleekPanther/minimum-weighted-vertex-cover-approximation-algorithm)  
    Approximation Algorithm for the NP-Complete problem of finding a **vertex cover of minimum weight** in a graph with weighted vertices. Guarantees an answers at most **2 times** the optimal minimum weighted vertex cover

## Python
- [Binary Hexadecimal Conversion](https://github.com/SleekPanther/binary-hexadecimal-conversion)  
Convert hex to binary & binary to hex
- [Alphabet Guessing Game (Python)](https://github.com/SleekPanther/alphabet-guessing-game)  
A very simple game to guess the numerical representation of a letter in the alphabet, or guess the letter from the number (A=1,B=2,...Z=26).  
A semi-trivial game, but I did this to try and teach myself to associate letters with numbers, not just the alphabetical order of letters

## C++
-  [Rush Hour Game](https://github.com/SleekPanther/rush-hour-game)  
Group Project creating a version of the board game **Rush Hour** in C++ using OpenGL & GLUT
