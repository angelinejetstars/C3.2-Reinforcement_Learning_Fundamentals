# Reinforcement Learning — Learn & Play 🤖

Welcome! This repository contains two Jupyter notebooks to help you understand **Q-learning** through hands-on practice.

## 📚 Notebooks

| Notebook | What you'll learn |
|---|---|
| **Original Q-Learning notebook** | Train a robot to move through a 4×4 grid and reach a goal. Learn states, actions, rewards, exploration vs. exploitation, and the Q-table. |
| [`Treasure_Hunter_Arena_Q_Learning.ipynb`](Treasure_Hunter_Arena_Q_Learning.ipynb) | Apply the same Q-learning logic to a 5×5 treasure hunt with walls, traps, and collectible gems. Experiment with rewards and watch the robot's behaviour. |

## 🚀 Getting started

1. **Download or clone** this repository and open it in **VS Code** or **Jupyter Notebook**.
2. Select a Python environment with `numpy`, `matplotlib`, `ipywidgets`, and `ipython` installed. If needed:
   ```bash
   pip install numpy matplotlib ipywidgets ipython notebook
   ```
3. **Start with the original notebook.** Run its cells from top to bottom.
4. Open **Treasure Hunter Arena** and run its cells from top to bottom.
5. In the interactive section, adjust the sliders and **retrain** the agent to see what changes.

## 🎮 Treasure Hunter challenge

Try changing:

- 💎 **Treasure reward:** Will the robot take a longer route to collect more gems?
- 💀 **Trap penalty:** Will it avoid dangerous squares?
- 👣 **Step penalty:** Can you encourage shorter routes?
- 🎲 **Exploration rate:** How does trying random moves affect learning?

**Your mission:** Find reward settings that help the robot collect valuable treasure, avoid traps, and reach the exit efficiently.

> **Remember:** The robot learns to maximise the reward *you define*. A high score does not always mean the shortest route.

## 💡 Key takeaway

**State → Action → Reward → Update Q-table → Repeat**

The Treasure Hunter game uses the same learning cycle as the original notebook, with a richer environment and an interactive experiment.

Happy experimenting! 🚀
