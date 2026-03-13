# Particle Swarm Optimization (PSO)

--------

## 📝 About the project
Hi, I'm Susanna! This project is a custom implementation of the Particle Swarm Optimization (PSO) algorithm. I developed it together with my classmate Claudia for the uzzy Systems & Evolutionary Computing course. PSO is an optimization algorithm inspired by the way birds flock or fish swim together. We built the core components from scratch to make them work perfectly with the `softpy` library interface!

--------

## 🛠️ Technologies/tools used
* **Python 3+** - The main programming language.
* **NumPy & SciPy** - For all the heavy math and matrix operations.
* **Matplotlib & Seaborn** - To draw the graphs and see how the swarm actually moves.
* **Softpy** - The evolutionary computing framework our code had to be compatible with.
* **Jupyter Notebook** - Where we wrote and tested everything.

--------

## ✨ Features
* **Custom Particle Class:** We created a `ParticleCandidate` class to manage each particle's position, velocity, and inertia.
* **PSO Algorithm:** A full `ParticleSwarmOptimizer` class that handles the population, evaluates fitness, and updates velocities using the standard PSO formula.
* **Algorithm Benchmarks:** We tested our swarm on famous mathematical functions (like Linear, Sphere, and the tricky Rastrigin function) to prove it actually finds the best solutions.
* **Fuzzy Systems Integration:** A practical example where we used our PSO to optimize Fuzzy Membership parameters.

--------

## 🚀 Process
We started by studying the math behind PSO: understanding how a single particle updates its speed by looking at its own best past position and the best position found by its neighbors. 
Then, we moved to the code. We used Object-Oriented Programming to build classes that inherited from the `softpy` library. The hardest part was making sure all the matrix operations with `numpy` were fast and correct. Finally, we set up test cases and plotted the results to visually check if the swarm was converging toward the right answer.

--------

## 🧠 What I learned
I learned how to code a Meta-heuristic Algorithm from scratch, which helped me finally understand how these techniques work under the hood, instead of just using them as a "black box". 
I also improved my Object-Oriented Programming skills in Python quite a bit, especially dealing with class inheritance. Plus, testing the algorithm on complex landscapes taught me a lot about the balance between *exploration* (looking around for new solutions) and *exploitation* (refining the good solutions we already found).

--------

## 🔧 How could it be improved
If we had more time to expand this project, I would try:
* **Dynamic Inertia:** Making the swarm start fast to explore, and then slow down to focus on the best area.
* **Different Swarm Rules:** Testing different ways particles talk to each other (like arranging them in a ring or star shape instead of just random neighbors).
* It would be super fun to use `matplotlib.animation` to create a real-time GIF of the particles flying around and finding the target!

--------

## ▶️ How to run the project

1. **Clone the repository:**
   Open your terminal and run:
   ```bash
   git clone [https://github.com/SusannaMazzocchi/Particle_Swarm_Optimization.git](https://github.com/SusannaMazzocchi/Particle_Swarm_Optimization.git)
   cd Particle_Swarm_Optimization
2. Install the required libraries:
   ```bash
   pip install numpy scipy matplotlib seaborn softpy

3. Open the Notebook:
   ```bash
   jupyter notebook main.ipynb
(Alternatively, you can use Google Colab)

