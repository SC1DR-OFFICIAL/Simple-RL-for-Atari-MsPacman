# Reinforcement Learning on Atari Ms. Pac-Man 🎮

This project explores **different Reinforcement Learning (RL) algorithms** applied to the classic Atari game **Ms. Pac-Man** using the [Gymnasium Atari](https://gymnasium.farama.org/) environments.

We implement, train, and compare several strategies:
- **Policy Gradient (REINFORCE)**
- **Random Search**
- **Hill Climbing**
- **Evolution Strategies**

## Project Goals 
1. Train an agent to play Ms. Pac-Man using various RL algorithms.
2. Visualize the training process (reward curves).
3. Record gameplay videos of the best episodes.
4. Compare algorithm performance and explain why some methods perform poorly.

## 📈 Training Curves

<p align="center">
  <table>
    <tr>
      <td align="center">
        <b>Policy Gradient (REINFORCE)</b><br>
        <img src="./plots/GradientPolicyProgress.png" width="420" alt="REINFORCE reward curve">
      </td>
      <td align="center">
        <b>Random Search</b><br>
        <img src="./plots/RandomSearchProgress.png" width="420" alt="Random Search reward curve">
      </td>
    </tr>
    <tr>
      <td align="center">
        <b>Hill Climbing</b><br>
        <img src="./plots/HillClimbingProgress.png" width="420" alt="Hill Climbing reward curve">
      </td>
      <td align="center">
        <b>Evolution Strategies</b><br>
        <img src="./plots/EvolutionStrategiesProgress.png" width="420" alt="Evolution Strategies reward curve">
      </td>
    </tr>
  </table>
</p>

> Curves show episode rewards over training steps for each algorithm.
