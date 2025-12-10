# 🐦 NEAT Flappy Bird AI  
### An AI that learns to play Flappy Bird using NeuroEvolution  
**Author:** Jay Patel  

This project implements an AI agent that learns to play Flappy Bird using the **NEAT (NeuroEvolution of Augmenting Topologies)** algorithm.  
A population of neural networks evolves over generations, improving their ability to survive obstacles and play the game autonomously.

---

## 🚀 Overview

The AI controls multiple birds in the game. Over time:

- Birds receive a fitness score based on how far they survive  
- NEAT evolves networks through mutation and selection  
- Birds learn to avoid pipes and stay alive longer  
- Eventually, the AI plays Flappy Bird with near-perfect precision  

This project showcases evolutionary algorithms, neural networks, and game simulation using Python.

---

## 🛠️ Tech Stack

- **Python 3.x**  
- **NEAT-Python** — neuroevolution library  
- **Pygame** — game rendering engine  
- **Object-Oriented Programming** for game entities and AI agents  

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/<pateljay9936>/AI_flappy_bird.git
cd AI_flappy_bird
```

### 2. Install dependencies
```bash
pip install neat-python pygame
```

### 3. Run the AI training
```bash
python flappy_bird.py
```

Watch as the AI learns and improves over generations!

---

## 📂 Project Structure

```
NEAT-Flappy-Bird/
│
├── flappy_bird.py            # main game loop + NEAT integration
├── bird.py                   # bird physics + neural network connections
├── pipe.py                   # pipe generation and movement
├── base.py                   # ground movement
├── config-feedforward.txt    # NEAT configuration
├── assets/                   # sprites & game images
└── README.md                 # project documentation (this file)
```

---

## 🎯 Features

- Autonomous AI gameplay  
- Neural network decision-making  
- Evolutionary training using NEAT  
- Real-time visualization with Pygame  
- Supports fast-forward and tweakable configuration  
- Fitness evaluation for better learning dynamics  

---

## 📚 Learning Outcomes (What I built & learned)

- Implemented NEAT evolutionary algorithms  
- Combined neural networks with game physics  
- Created a full Pygame environment for AI training  
- Designed fitness functions for reinforcement-style learning  
- Learned optimization techniques for faster evolutionary convergence  

---

## 📺 Demo (Optional)

If you upload a gameplay video or GIF, embed it here:

```
![Flappy Bird AI Demo](demo.gif)
```

---

## 👤 Author

**Jay Patel**  
- GitHub: https://github.com/pateljay9936  
- LinkedIn: https://linkedin.com/in/pateljay9936  

---

## ⭐ Acknowledgment

This project is inspired by educational resources on neural networks and neuroevolution.  
The implementation, structure, and enhancements are created and customized by **Jay Patel**.