# Soft-Actor-Critic-SAC-LunarLander-Continuous-Action

This repository contains an implementation of the **Soft Actor-Critic (SAC)** algorithm applied to the **LunarLander-v3** environment with continuous action space.

The SAC agent learns a stochastic policy for controlling the lander, achieving stable and efficient landings.

---

## Files

- `final_continuous_lunar.ipynb` — Main notebook implementing SAC, training, checkpointing, and evaluation.  
- `cont_lunar_lander_q_network.pth` — Trained actor network.  
- `lunar_lander_demo.mp4` — Video of the trained agent performing landings.  
- `requirements.txt` — Python dependencies (optional).  

---

## Training Summary

- The model reached an **average reward of over 500** on the last 100 episodes.  
- **Training duration:** 603 episodes.  
- **Evaluation performance:** Average reward of **247.597** over 50 evaluation episodes.  

> Note: The evaluation was run using a deterministic policy to assess average performance.

---

## How to Run

1. Clone this repository:
```bash
git clone <repository-url>
cd SAC_LunarLander

