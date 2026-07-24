# DAA Experiment 6 – Matrix Chain Multiplication using Dynamic Programming

This repository contains the implementation of **Experiment 6** for the **Design and Analysis of Algorithms (DAA)** laboratory. The program solves the **Matrix Chain Multiplication (MCM)** problem using the **Dynamic Programming** approach to determine the optimal order of matrix multiplication with the minimum number of scalar multiplications.

## 📌 Objective

To implement the **Matrix Chain Multiplication** algorithm using **Dynamic Programming** and determine:

- The minimum number of scalar multiplications.
- The optimal parenthesization of the matrix chain.
- The Dynamic Programming cost table.

## 🧠 Algorithm

1. Represent the dimensions of the matrices in an array.
2. Initialize DP tables for storing minimum multiplication costs and split positions.
3. Compute the minimum multiplication cost for chains of increasing length.
4. Store the optimal split point for each subproblem.
5. Generate the optimal parenthesization using the split table.
6. Display the minimum cost, optimal parenthesization, and DP cost table.

## ✨ Features

- Dynamic Programming solution for Matrix Chain Multiplication.
- Calculates the minimum scalar multiplication cost.
- Displays the optimal parenthesization.

## 🛠️ Technologies Used

- **Language:** Python 3
- **Concept:** Dynamic Programming
- **IDE:** VS Code / PyCharm / IDLE

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/Swaminathaan17/DAA-Exp6.git
```

2. Navigate to the project folder:

```bash
cd DAA-Exp6
```

3. Run the program:

```bash
python matrix_chain.py
```

## 📖 Learning Outcomes

- Understand the Dynamic Programming paradigm.
- Learn how Matrix Chain Multiplication optimization works.
- Analyze optimal substructure and overlapping subproblems.
