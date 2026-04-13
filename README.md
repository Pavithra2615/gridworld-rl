# gridworld-rl
# 🎮 Grid World Game using Reinforcement Learning

## 📌 Project Overview

This project implements a simple **Grid World Game** where an agent learns to reach a goal while avoiding penalties using **Policy Iteration**.

---

## 🧠 Concepts Used

* Reinforcement Learning
* Markov Decision Process (MDP)
* Policy Iteration

---

## 🗺️ Environment

3x3 Grid:

S  .  .
.  X  .
.  .  G

* S → Start
* G → Goal (+10 reward)
* X → Penalty (-10 reward)

---

## 🎮 Actions

* Up
* Down
* Left
* Right

---

## 🎯 Rewards

* Goal → +10
* Penalty → -10
* Normal step → -1

---

## ⚙️ Algorithm

1. Initialize random policy
2. Evaluate policy
3. Improve policy
4. Repeat until optimal

---

## 💻 Implementation

* Python
* NumPy

---

## ▶️ How to Run

1. Open in Google Colab
2. Run all cells
3. Observe optimal policy

---

## 📊 Output Example

Optimal Policy:
State 0 -> Action 1
State 1 -> Action 3
State 2 -> Action 1

---

## 🚀 Future Improvements

* Add Q-learning
* Add visualization
* Larger grid

---

## 👨‍💻 Author

Pavithra
