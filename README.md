# ♞ Knight's Tour Solver using Genetic Algorithm (Python + Pygame)

This project solves the classical **Knight's Tour** problem using a
**Genetic Algorithm (GA)**.\
The objective is to move a knight on an 8×8 chessboard and visit all 64
squares **exactly once**.\
The solver evolves a population of knights until one reaches a full
valid tour, then visualizes the solution using **Pygame**.

------------------------------------------------------------------------

## 📌 Features

-   Full Genetic Algorithm implementation:
    -   Random chromosome initialization
    -   Tournament selection
    -   Single-point crossover
    -   Mutation with adjustable rate
    -   Fitness evaluation based on visited squares
-   Intelligent move correction system (forward/backward cycling)
-   Automatic population evolution until a valid tour (fitness = 64)
-   Clean, object-oriented architecture (Chromosome, Knight, Population)
-   Pygame animation showing:
    -   Knight's path
    -   Move order
    -   Lines connecting the sequence
    -   Start and end highlights

------------------------------------------------------------------------

## 📁 Project Structure

    project-folder/
    │
    ├── src/
    │   └── knights_tour_ga.py
    │
    ├── README.md
    ├── requirements.txt
    └── .gitignore

------------------------------------------------------------------------

## 📦 Installation

``` bash
pip install -r requirements.txt
```

requirements.txt:

    pygame

------------------------------------------------------------------------

## ▶️ Running the Program

``` bash
python src/knights_tour_ga.py
```

------------------------------------------------------------------------

## 🧬 Genetic Algorithm Overview

### Chromosome

-   63 genes\
-   Each gene ∈ {1..8}\
-   Single-point crossover\
-   Mutation (random gene replacement)

### Knight

-   position\
-   path\
-   chromosome\
-   fitness\
-   move validation\
-   forward/backward cycle correction

### Population

-   tournament selection (size 3)
-   crossover + mutation
-   stops when fitness = 64

------------------------------------------------------------------------

## 🎮 Pygame Visualization

-   Chessboard\
-   Red path dots\
-   Blue connecting lines\
-   Move numbers\
-   Start = green\
-   End = yellow\
-   Fitness display



------------------------------------------------------------------------

## 👤 Author

**Mohamed Amine Sellami**

------------------------------------------------------------------------

## Uploaded Files (Reference)

Python code:

    /mnt/data/73cb9af7-45ec-4575-83c8-ea8adb07b0e8.py

Project instructions:

    /mnt/data/Project 2.pdf
