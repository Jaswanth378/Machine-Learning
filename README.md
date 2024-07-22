# Multi-Armed Bandit Problem Simulation

This project implements a simulation of the Multi-Armed Bandit problem using the epsilon-greedy algorithm. It demonstrates the exploration-exploitation trade-off in reinforcement learning.

## Description

The Multi-Armed Bandit problem is a classic reinforcement learning problem where an agent must choose between multiple actions (arms) to maximize its cumulative reward. This implementation simulates a bandit with a specified number of arms, each with a different reward distribution.

## Features

- Configurable number of arms
- Epsilon-greedy algorithm for action selection
- Visualization of average rewards and optimal action selection over time
- Comparison of true vs. estimated action values
- Multiple runs for statistical reliability

## Requirements

- Python 3.x
- NumPy
- Matplotlib

## Usage

1. Set the parameters at the bottom of the script:
   - `n`: Number of arms
   - `std_range`: Range for generating random standard deviations
   - `steps`: Total number of plays
   - `epsilons`: List of epsilon values to test
   - `runs`: Number of runs for averaging results

2. Run the script:
3. The script will generate plots showing:
- Average reward over time for different epsilon values
- Percentage of optimal action chosen over time
- True vs. estimated action values
- Reward distribution between true and estimated action values

## Code Structure

- `MultiArmedBandit` class: Implements the bandit environment and action selection logic
- `run_bandit` method: Runs a single bandit simulation
- `plot_results` function: Visualizes the results of the simulation

## Results

The script outputs:
- Graphical plots of the simulation results
- True standard deviations for each arm
- True action values
- Estimated action values after the simulation

## Author

Jaswanth Kattubavi Sreenivasulu
