# Informed Search
### - This repo consists of the Informed search based Shortest Path in Binary Maze question Using:

    1. Best First Search

    2. A_Star

---
---

## Question (Binary Maze):
```You are given an n × n binary matrix grid. Your task is to implement and compare two```
```search algorithms to find a path from the top-left cell (0, 0) to the bottom-right cell (n```
```- 1, n - 1).```

```A clear path is defined as:```
    ```1.​ All visited cells along the path must have a value of 0.​
    2.​ Moves can be made 8-directionally — i.e., from a cell, you may move to another
        cell that is horizontally, vertically, or diagonally adjacent.​
    3.​ The length of the path is the total number of visited cells.
​```

---

## ***Approach***
### 1. **Represent State**:
>Store the position i and the j 

### 2. **Identify Goal**:
>Determine the final Goal like n-1 and n-1

### 3. **Generate all valid Children**:
>From each State Generate all possible valid Children like try to move from every cell to all other 8 directions 

``` for example if the State is [[0, 0, 0],[0, 1, 0],[0, 0, 0]]:```

``` Then all valid moves are: ```
```
i:1,j:0,cost:1
i:0,j:1,cost:1
```

### 4. **Perform GBFS**:
>Take two List `OPEN` and `CLOSED` and push the start into `OPEN` and pop the element from `OPEN` based on the `h()` value and push it into `CLOSED` and check `goalTest()` and generate all Child of poped elements and push `OPEN` and repeat until `OPEN` is not empty 

### (OR)

### **Perform A_Star**:
>Take two List `OPEN` and `CLOSED`  and `g` actual cost and `f = g + h` and push the start into `OPEN` and pop the element from `OPEN` based on the `f()` value and push it into `CLOSED` and check `goalTest()` and generate all Child of poped elements and `propagateImprovement()` until `OPEN` is not empty

### 5. **Print Path**:
> If `goalTest()` return true reconstruct the path by backtracking it's parent in the `CLOSED`

---
---


## Conculsion
    This repository contains the complete solutions of the question Using both Approaches. 
    If you have any questions feel free to open a issue.

---
    Thank you for Visitng!


📧 **Email**: badamvenkatesh2007@gmail.com  
🔗 **LinkedIn**: [Badam Venkatesh](https://linkedin.com/in/badamvenkatesh)  
💻 **GitHub**: [Venkatesh2007](https://github.com/Venkatesh2007)


