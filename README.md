# Knight-s-Tour-Solver-using-Genetic-Algorithm-Python-Pygame-

This project solves the classical **Knight’s Tour** problem using a **Genetic Algorithm (GA)**.  
The objective is to move a knight on an 8×8 chessboard and visit all 64 squares **exactly once**.  
The solver evolves a population of knights until one reaches a full valid tour, then visualizes the
solution using **Pygame**.

---

## 📌 Features

- Full Genetic Algorithm implementation:
  - Random chromosome initialization
  - Tournament selection
  - Single-point crossover
  - Mutation with adjustable rate
  - Fitness evaluation based on visited squares
- Intelligent move correction system (forward/backward cycling)
- Automatic population evolution until a valid tour (fitness = 64)
- Clean, object-oriented architecture (Chromosome, Knight, Population)
- Pygame animation showing:
  - Knight’s path
  - Move order
  - Lines connecting the sequence
  - Start and end highlights

---

## 📁 Project Structure

project-folder/
│
├── tprp2.py # Full implementation (GA + interface)
│
├── README.md
├── requirements.txt
└── .gitignore

yaml
Copy code

If you used the uploaded file, place it inside:
`src/knights_tour_ga.py`

---

## 📦 Installation

Install dependencies:

```bash
pip install -r requirements.txt
requirements.txt

nginx
Copy code
pygame
.gitignore (recommended)

markdown
Copy code
__pycache__/
*.pyc
.vscode/
.idea/
▶️ Running the Program
Run the Genetic Algorithm:

bash
Copy code
python src/knights_tour_ga.py
The script:

Generates an initial population of knights

Evolves the population using the GA

Stops when a knight achieves a perfect tour (64 visited squares)

Displays the solution using a Pygame interface

🧬 Genetic Algorithm Overview
Chromosome
Length: 63 genes

Each gene ∈ {1..8} → one of the 8 knight moves

Includes:

Random initialization

Single-point crossover

Mutation (by randomizing moves)

Knight
Attributes:

position

chromosome

path (visited squares)

fitness (1–64)

Validates and corrects moves using:

Forward/backward cycle strategy

Avoids illegal and repeated positions

Population
Tournament selection (size = 3)

Creates new generation with crossover + mutation

Evolution continues until a full tour is found

🎮 Pygame Visualization
The interface shows:

Chessboard with correct colors

Visited squares (red circles)

Move numbers inside each square

Blue path lines connecting the sequence

Green → starting square

Yellow → current ending square

Fitness and steps displayed in real-time

📘 Example Output (Console)
java
Copy code
Generation 1  | Best Fitness = 32
Generation 2  | Best Fitness = 37
Generation 3  | Best Fitness = 41
...
Generation 23 | Best Fitness = 64
Solution found!


👤 Author
Mohamed Amine Sellami
Full-Stack Developer & Visual Computing Master’s Student.

🔗 Local uploaded files (reference)
Python code:

bash
Copy code
/mnt/data/73cb9af7-45ec-4575-83c8-ea8adb07b0e8.py
PDF instructions:

bash
Copy code
/mnt/data/Project 2.pdf
yaml
Copy code

---







