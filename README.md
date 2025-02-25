# Rubix-Cube-Solver
🧩 Rubik's Cube Solver
📌 Introduction
The Rubik’s Cube Solver is a C++ program that models and solves a 3x3 Rubik’s Cube using computational algorithms. It allows users to input a scrambled cube and receive step-by-step instructions to solve it efficiently.

🚀 Features
✅ Models a virtual Rubik’s Cube using C++ data structures
✅ Implements various move operations (rotations, flips, turns)
✅ Uses graph-based search algorithms to find an optimal solution
✅ Displays the cube’s state before and after solving
✅ Efficient and scalable approach

🔧 Installation
1️⃣ Clone the repository
sh
Copy
Edit
git clone https://github.com/spandanbali/Rubix-Cube-Solver.git
cd Rubix-Cube-Solver
2️⃣ Compile the program
sh
Copy
Edit
g++ -o solver main.cpp
3️⃣ Run the solver
sh
Copy
Edit
./solver

🎮 Usage
Input a scrambled cube state manually or through a file
The program will process the input and compute the solution
Step-by-step solving instructions will be displayed

🧠 Algorithms Used
Graph Representation: Cube states are treated as nodes, moves as edges
Breadth-First Search (BFS): Finds the shortest path to a solved state
Kociemba’s Algorithm (Optional): More efficient solving approach

📈 Future Improvements
🔹 GUI Interface for better visualization
🔹 Support for multiple cube sizes (2x2, 4x4, etc.)
🔹 More optimized solving algorithms
