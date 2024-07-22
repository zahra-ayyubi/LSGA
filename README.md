# LSGA-Sudoku-Solver

This project implements a Local Search Genetic Algorithm (LSGA) to solve Sudoku puzzles. The algorithm combines genetic operations with local search strategies to efficiently solve Sudoku puzzles of varying difficulty levels.
For more details on the algorithm, refer to the original paper: https://ieeexplore.ieee.org/document/10015696


## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Requirements](#requirements) 

## Introduction

The LSGA-Sudoku-Solver is designed to solve Sudoku puzzles using a novel evolutionary algorithm that incorporates column and sub-block local search techniques. This approach enhances the convergence speed and accuracy of finding the optimal solution. For more details on the algorithm, refer to the [original paper](https://ieeexplore.ieee.org/document/10015696).

## Project Structure
LSGA-Sudoku-Solver
additional_studies_output/ # Output of additional studies
demo/ # Directory for demo purposes
output/ # Directory to store general output files
paper_six_puzzle_experiment_output/ # Output of paper's six puzzle experiment
puzzles/ # Directory containing Sudoku puzzles
additional_studies.ipynb # Jupyter Notebook for additional studies
LSGA_main.ipynb # Main Jupyter Notebook for running LSGA
README.md # This README file
requirements.txt # List of required Python packages


## Requirements

To run this project, you need Python 3.x and the following packages:

- numpy
- pandas
- matplotlib
- openpyxl

You can install the required packages using pip:

```sh
pip install -r requirements.txt
