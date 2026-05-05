# 🚦 Reinforcement Learning for Traffic Flow Optimization

## 📌 Overview

This project uses Reinforcement Learning (RL) to optimize traffic signal control at an intersection. Traditional traffic systems use fixed timers and fail to adapt to real-time traffic conditions. This project builds an intelligent agent that dynamically controls traffic signals to reduce congestion and waiting time.

---

## 🧠 Problem Statement

Traffic congestion leads to:

* Increased waiting time
* Fuel wastage
* Poor traffic flow

👉 Goal: Design an RL-based system that learns optimal traffic signal switching.

---

## ⚙️ Methodology

### 🔹 Markov Decision Process (MDP)

* **States:** Queue length of vehicles (North, South, East, West)
* **Actions:** Traffic signal phases (NS Green / EW Green)
* **Reward:**

  * Negative waiting time
  * Negative queue length

---

### 🔹 Algorithm Used

Q-Learning / Deep Q-Network (DQN)


---

## 🔄 Workflow

1. Observe traffic state
2. Select action using RL policy
3. Apply traffic signal phase
4. Receive reward
5. Update model

---

## 📊 Results

Compared to traditional fixed-time signals:

* Reduced waiting time (20–60%)
* Lower queue length
* Improved traffic throughput

---

## ▶️ Run the Project

Click below to open directly in Google Colab:

[![Open in Colab](https://colab.research.google.com/github/jenniferfrancisss/traffic-rl-optimization/blob/main/RLAI_traffic_flow_optimize.ipynb)

---

## 📁 Project Structure

traffic-rl-optimization/
│── rlai-capstone.ipynb
│── README.md

---

## 🔮 Future Scope

* Multi-intersection optimization
* Real-time traffic sensor integration
* Multi-agent reinforcement learning

---

## 🛠️ Tech Stack

* Python
* Reinforcement Learning
* Google Colab

---

## 👤 Author

Jennifer Francis
