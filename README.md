# FrozenLake 8x8 Q-Learning

This project uses tabular Q-learning to train an agent in Gymnasium's 8 x 8 FrozenLake environment. The agent tries to reach the goal while avoiding holes on a slippery map.

The project includes a baseline training run and experiments with different learning rates, discount factors, and epsilon-decay values.

## Setup

This project uses Python, Gymnasium, NumPy, and Matplotlib.

Install the needed packages with:

```bash
pip install "gymnasium[other]" numpy matplotlib

Run Instructions
Open the Jupyter Notebook included in this repository.
Run the cell. The code trains the baseline agent, runs the hyperparameter experiments, evaluates the final agent, saves the graphs, and creates a video of the trained agent.

Results
The code saves these files in the results folder:
- baseline.png - baseline training plot
- alpha.png - learning-rate experiment plot
- gamma.png - discount-factor experiment plot
- decay.png - epsilon-decay experiment plot
- frozenlake_agent-episode-0.mp4 - video of the final trained agent

The notebook also prints the best configuration, success rates, and average number of steps for the baseline and best agent.
```
