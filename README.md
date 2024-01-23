# COMP4605 Project: Project Partner Assignment Tool

## Overview

This Python tool is designed to automate the assignment of project partners for the Data Mining course mini-projects. The tool takes input preferences from students and utilizes optimization algorithms to generate project partnerships, considering the specified preferences.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/comp4605-project.git
   cd comp4605-project

2. Install dependencies:
   ```bash
   pip install -r requirements.txt


## Usage
1. Provide input preferences in a text file named preferences.txt following the format mentioned in the project description.
2. Run the main script.
3. Choose an optimizer from the options presented (Random, Hill Climbing, Simulated Annealing, Genetic).
4. View the optimized project partnerships and total cost.

## Project Structure
- main.py: Main script to run the project partner assignment tool.
- optimizer.py: Contains optimization algorithms (Hill Climbing, Simulated Annealing, Genetic).
- utils.py: Utility functions for loading preferences, calculating cost, etc.

## Customization
- Modify the preferences.txt file to include the preferences of each student.
- Adjust optimization parameters in the code (e.g., population size, generations, probabilities) for Genetic Algorithm.

