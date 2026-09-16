# Huggy — Reinforcement Learning with Unity ML-Agents

A hands-on deep reinforcement learning project where I trained **Huggy**, a virtual dog agent, to learn behaviors using Unity ML-Agents and the PPO (Proximal Policy Optimization) algorithm.

## 🎯 Project Overview
This project is part of my deep RL learning journey. Huggy is a pre-built Unity environment where an agent (a dog) learns to interact with its environment through trial and reward, using reinforcement learning.

## 🛠️ Tools & Tech
- Unity ML-Agents
- PPO (Proximal Policy Optimization)
- Python, Google Colab
- Config: [`config/Huggy.yaml`](config/Huggy.yaml)

## ⚙️ Setup
1. Clone [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents)
2. Install dependencies:
   ```
   pip install -e ./ml-agents-envs
   pip install -e ./ml-agents
   ```
3. Run training:
   ```
   mlagents-learn ./config/Huggy.yaml --env=<path-to-Huggy-executable> --run-id="Huggy" --no-graphics
   ```

## 📊 Results
_(to be added — training in progress)_

## 🎥 Demo
_(to be added)_

## 📚 What I Learned
_(to be added)_

## 🔗 References
- [Unity ML-Agents Toolkit](https://github.com/Unity-Technologies/ml-agents)
- [Hugging Face Deep RL Course](https://huggingface.co/learn/deep-rl-course)
