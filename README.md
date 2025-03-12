# Deep Reinforcement Learning
## 1. Lunar Landing

This repository contains a trained model of a **Proximal Policy Optimization (PPO)** agent playing the **LunarLander-v2** environment using the **stable-baselines3** library. The model is hosted on the [Hugging Face Hub](https://huggingface.co/Phani0404/Lunar_Landing).

### Overview

- **Environment**: The **LunarLander-v2** environment is a classic problem in reinforcement learning where an agent must land a lunar module safely on the moon's surface.
- **Model Architecture**: The agent uses a **MultiLayerPerceptron (MLP) Policy** since the input is a vector. If the input were frames, a **CnnPolicy** would be used.
- **Training Parameters**:
  - **Total Timesteps**: 1,000,000
  - **Policy**: PPO
  - **Batch Size**: 64
  - **Number of Epochs**: 4
  - **Gamma**: 0.999
  - **GAE Lambda**: 0.98
  - **Entropy Coefficient**: 0.01

### Evaluation Results

- **Mean Reward**: 249.36 +/- 18.56 (evaluated over 10 episodes with deterministic=True)




