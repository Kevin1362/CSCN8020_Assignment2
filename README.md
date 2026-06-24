# CSCN8020 Assignment 2: Taxi Gymnasium Environment with Q-Learning

## Student Information

Name: Kevinkumar Patel  
Student ID: 8998612 

## Project Summary

This project implements the Q-Learning algorithm on the Taxi Gymnasium environment. The goal is to train an agent to navigate the grid world, pick up a passenger, and drop the passenger at the correct destination. The notebook includes an object-oriented implementation, baseline training, hyperparameter experiments, training metrics, plots, policy evaluation, logging, and final interpretation.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR_GITHUB_ID/CSCN8020_Assignment2.git
```

2. Open the folder:

```bash
cd CSCN8020_Assignment2
```

3. Install requirements:

```bash
pip install -r requirements.txt
```

4. Run the notebook:

```bash
jupyter notebook CSCN8020_Assignment2.ipynb
```

## Major Files

- `CSCN8020_Assignment2.ipynb`: Main notebook with Q-Learning implementation and explanation.
- `requirements.txt`: Required Python packages.
- `.gitignore`: Files and folders excluded from GitHub.
- `logs/assignment2_execution.log`: Log file showing training progress.
- `images/`: Folder containing generated plots.

## Q-Learning Implementation

The solution uses a Q-table to store state-action values. The agent uses epsilon-greedy action selection to balance exploration and exploitation. After each step, the Q-table is updated using the Q-Learning update rule based on reward and estimated future value.

## Repository Link

https://github.com/YOUR_GITHUB_ID/CSCN8020_Assignment2
