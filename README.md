# Multi-Armed Bandit Strategies - Reinforcement Learning

This Python script demonstrates two different strategies for solving multi-armed bandit problems. Multi-armed bandits involve decision-making under uncertainty, where an agent must choose between multiple actions to maximize cumulative rewards. In this script, we explore the following strategies:

## Upper Confidence Bound (UCB)

The UCB strategy aims to balance exploration and exploitation by selecting actions with the highest estimated upper bound of reward. The script reads a dataset from an Excel file and uses the UCB algorithm to select actions over a specified number of rounds (T). After the selections, it plots a histogram that shows how often each action was chosen.

## Thompson Sampling (Beta Distribution)

Thompson Sampling is another strategy for multi-armed bandit problems. It models the reward distribution for each action using Beta distributions and samples from these distributions to decide which action to take. The script implements this approach by randomly selecting actions over a specified number of rounds (N) and then creates a histogram to visualize the frequency of each action's selection.

## Prerequisites

Before using this script, ensure you have the following prerequisites:

- Python (3.6+)
- Required libraries: NumPy, Matplotlib, Pandas
- Jupyter Notebook or a Python environment that supports the execution of Jupyter notebooks

You can install the necessary libraries using pip:

```bash
pip install numpy matplotlib pandas
```

## Usage

1. Open the Jupyter Notebook provided in this project.

2. Execute each cell in the notebook to run the script step by step.

3. The script will demonstrate the two multi-armed bandit strategies and provide visualizations of action selections.

4. Customize the parameters or dataset in the script to experiment with different scenarios.

Feel free to explore and adapt this script for your own multi-armed bandit problems or reinforcement learning projects.
