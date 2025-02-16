# Dynamic Programming in FrozenLake: Policy Iteration and Value Iteration 🧊🤖

## Project Description 📝
This project implements **Dynamic Programming algorithms**, specifically **Policy Iteration** and **Value Iteration**, to solve the FrozenLake environment in OpenAI Gym. The goal is to find the optimal policy that allows the agent to navigate from the starting point to the goal without falling into holes. The project includes the implementation of policy evaluation, policy improvement, and value iteration algorithms, and tests them on two versions of the FrozenLake environment: a 5x5 grid with a bridge and a larger 15x9 grid.

## Requirements 📦
To run this project, you will need the following Python libraries:
- `gym`
- `numpy`
- `matplotlib`
- `pygame`
- `pyvirtualdisplay`

You can install the dependencies by running:
```bash
pip install gym numpy matplotlib pygame pyvirtualdisplay
```

## Project Structure 🗂️
The project is organized into the following sections:
1. **Dependencies Installation**: Installs the necessary libraries to run the FrozenLake environment and plot results.
2. **Utility Functions**: Defines functions to plot the value function and run the agent in the environment.
3. **Algorithm Implementations**:
   - **Policy Evaluation**: Iterative evaluation of a given policy.
   - **Policy Improvement**: Policy improvement based on the value function.
   - **Policy Iteration**: Combines policy evaluation and improvement to find the optimal policy.
   - **Value Iteration**: Value iteration to find the optimal value function and corresponding policy.
4. **Testing on FrozenLake**:
   - **FrozenLake 5x5 with Bridge**: Tests the algorithm on a small grid with a bridge.
   - **FrozenLake 15x9**: Tests the algorithm on a larger and more complex grid.
5. **Algorithm Comparison**: Compares the execution time and performance of Policy Iteration and Value Iteration.

## Usage 🚀
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dynamic-programming-frozenlake.git
   cd dynamic-programming-frozenlake
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the file `Dynamic_Programming_in_FrozenLake.ipynb` and follow the instructions to execute the cells.

### Expected Output:
- The project includes plots of the value function and the optimal policy for both environments. The visualizations will show:
  - **State Value Function**: The expected return from each state.
  - **Optimal Policy**: The best action to take at each state.

## Results 📊
- The project demonstrates the agent's performance in each environment after applying the Policy Iteration and Value Iteration algorithms. The plots show how well the agent is able to navigate the FrozenLake environments and the comparison between the two algorithms.

## Contributions 🤝
Contributions are welcome! If you find any issues or have suggestions to improve the project, please open an issue or submit a pull request.
