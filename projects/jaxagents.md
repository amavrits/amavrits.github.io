---
layout: single
title: "JAXAgents: a package for efficient (Multi-Agent) Reinforcement Learning"
permalink: /projects/jaxagents/
---

JAXAgents is a high-performance (Multi-Agent) Reinforcement Learning library built on [JAX](https://github.com/google/jax), designed for rapid experimentation, scalable training of RL agents and fast hyperparameter tuning. It supports a variety of algorithms and environments, making it suitable for both research and practical applications.

&nbsp;<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20" style="vertical-align: middle; margin: 0 0 0.5rem 0;"/>
<a href="https://github.com/amavrits/jax-agents" class="white-link">JAXAgents</a><br/>
    
Also available on [PyPI](https://pypi.org/project/jaxagents/)

## 🛠️ Features

- **RL**: Implementations of popular RL algorithms, including:
  - **Q-learning**:
    - Deep Q Networks (DQN)
    - Double Deep Q Networks (DDQN)
    - Categorical DQN (C51)
    - Quantile Regression DQN (QRDQN)
  - **Policy Gradient**:
    - REINFORCE
    - Proximal Policy Optimization (PPO) with Generalized Advantage Estimation (GAE)
  - **Multi-Agent RL**:
    - Independent PPO (IPPO)

- **High Performance**: Leveraging JAX's capabilities for just-in-time compilation and automatic differentiation, enabling efficient computation on CPUs and GPUs.

- **Modular Design**: Structured for easy extension and customization, facilitating experimentation with new algorithms and environments.

## 🏁 Getting Started

Here's a simple example to train a PPO agent:

```python
import jaxagents

# Initialize environment and agent
env = jaxagents.environments.make('CartPole-v1')
agent = jaxagents.agents.PPO(env)

# Train the agent
agent.train(num_episodes=1000)
```

For more detailed examples and usage, refer to the [documentation](https://jax-agents.readthedocs.io/en/latest/).

## 🚀 Performance

JAXAgents enables extremely fast optimization. Below is an example of a PPO agent trained on CartPole-v1 — achieving near-optimal performance within approximately 100 episodes:

<p align="center">
  <img src="/assets/cartpole_returns.png" alt="Training Returns on CartPole-v1" />
</p>

<p align="center">
  <em>Minimum and maximum returns per training episode.<br>JAXAgents enables lightning-fast learning: PPO solves CartPole-v1 in approximately 100 episodes.</em>
</p>

## 📖 Documentation

Comprehensive documentation is available at [amavrits.github.io](https://amavrits.github.io/jax-agents/), covering:

- Installation and setup
- Detailed API references
- Tutorials and examples
- Advanced topics and customization

