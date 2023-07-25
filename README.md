# Quantum Dot Analysis Project

## Introduction

This is a project I worked on for my computational module in my second year. This project explores the computational analysis of energy eigenstates in an infinite square well potential. The main goal is to study the behavior of quantum systems using numerical methods and compare the results with analytical solutions for verification. Additionally, the project explores the analysis of different types of potentials, including the harmonic potential and a finite potential within an infinite potential.

## Methods Used

The project employs two main computational methods:

1. **Runge-Kutta Method (2D):** This numerical technique is used to solve ordinary differential equations (ODEs) that arise in the time-independent Schrödinger equation. The method provides accurate approximations for energy eigenstates of quantum systems.

2. **Secant Method:** The secant method is utilized to find solutions to the Schrödinger equation, particularly to determine the energy eigenvalues.

## Getting Started

To reproduce the results of this project, follow these steps:

1. **Python Installation:**

   If you don't have Python installed, download and install it from the official website: https://www.python.org/downloads/

2. **Clone the Repository:**

   Clone or download the project repository to your local machine.

3. **Install Dependencies:**

   Open your terminal or command prompt, navigate to the project directory, and install the required libraries `numpy` and `matplotlib`:

   ```
   pip install numpy matplotlib jupyter
   ```

4. **Run the Jupyter Notebook:**

   Launch Jupyter Notebook by running the following command in your terminal or command prompt:

   ```
   jupyter notebook
   ```

   This will open Jupyter Notebook in your web browser.

5. **Open and Run the Notebook:**

   Inside Jupyter Notebook, click on the `Quantum_dot_analysis.ipynb` file to open it. Run the code cells by clicking cell and then run all.

## Analysing Different Potentials

### Harmonic Potential

For Harmonic potential, I modify the Schrödinger equation according to the harmonic potential and utilise the computational methods to find the eigenstates. I use Hermite polynomials to calculate the analytical solutions.

### Finite Potential within an Infinite Potential

I also look at a situation where a finite potential well is embedded within a infnite potential well. I apply the necessary adjustments to the Schrödinger equation for this potential configuration and calculate the corresponding energy eigenstates using computational methods.
In this case, there isn't a analytical solution to compare my results to.

## Conclusion

The Quantum Dot Analysis Project offers a thorough analysis of energy eigenstates in various potential configurations using computational methods. By comparing my numerical results with analytical solutions, I establish the accuracy and reliability of the approach. The modifications applied to the secant method ensure the calculation of relevant energy eigenstates for diverse potentials without skipping energy levels. As analytical solutions are not always be available, computational methods become crucial in finding energy eigenstates for unknown potentials. Therefore, it is essential to think of an efficient and accurate computational techniques to calculate these solutions.

While I explored my own adaptation of the secant method, I acknowledge that there is room for optimisation. Currently, the code may run relatively slower when solving Schrödinger equations for different potentials. Moreover, due to inherent limitations in the secant method, it has a tolerance level that restricts the identification of closely spaced energy levels. I am eager to further explore optimization possibilities to enhance the efficiency of my code.

Feel free to try the code provided in this repository. Your constructive contributions and improvements are welcomed!
