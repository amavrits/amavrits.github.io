---
layout: single
title: "Hunting Game – A Web-Based Prey-Predator AI Experience powered via Multi-Agent Reinforcement Learning"
permalink: /projects/hunting-game/
---

Welcome to the **Hunting Game**, an interactive single-player game where you play as the prey or predator against trained AI agents!

This project showcases the power of **Multi-Agent Reinforcement Learning (MARL)** using a custom environment and agents trained with **Independent Proximal Policy Optimization (IPPO)**, all wrapped in a web-based interface.

<p align="center">
  <img src="/assets/hunting_game_v1.gif" alt="Hunting Game animation" />
</p>


## 🎮 Gameplay Features

- 🧠 **Smart AI agents** trained with [JAXAgents](https://github.com/amavrits/jax-agents), JAX, Flax, and Optax  
- 🎭 **Play as prey or predator** against AI with unique strategies  
- 🕹️ **Cross-platform controls**: keyboard or on-screen joystick  
- 🌐 **Browser-based** — no installation required  
- 🔄 **Replayable** with different roles and strategies  
- 📹 **Game recording** for agent fine-tuning (coming soon)  

---

## 🧠 Tech Stack

| Component           | Technology                                                                                         |
|---------------------|----------------------------------------------------------------------------------------------------|
| **RL Agents**       | <a href="https://github.com/amavrits/jax-agents" class="gold-link">JAXAgents</a>, JAX, Flax, Optax |
| **Algorithm**       | Improved PPO (IPPO)                                                                                |
| **Environment**     | Custom prey-predator grid setup                                                                    |
| **Frontend**        | HTML, CSS, JavaScript                                                                              |
| **Mobile Input**    | On-screen joystick                                                                                 |
| **Backend API**     | FastAPI                                                                                            |
| **Containerization**| Docker                                                                                             |
| **Hosting**         | GitHub Pages (frontend), Hetzner Cloud (backend)                                                   |

---

## 💡 Roadmap

- 🎮 Add human vs. human multiplayer mode  
- 📈 Implement curriculum learning for progressive difficulty  
- 📊 Create analytics dashboard (reward curves, agent heatmaps)  
- 🎨 Polish UI/UX with animations and tutorials  

---

Made with passion for gaming and AI 

Trained using [JAXAgents](https://github.com/amavrits/jax-agents) based on JAX & Flax, and deployed via FastAPI.
