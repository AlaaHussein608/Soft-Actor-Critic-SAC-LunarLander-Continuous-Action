# Soft-Actor-Critic-SAC-LunarLander-Continuous-Action

This repository contains an implementation of the **Soft Actor-Critic (SAC)** algorithm applied to the **LunarLander-v3** environment with continuous action space.

The SAC agent learns a stochastic policy for controlling the lander, achieving stable and efficient landings.

---

## Files

- `final_continuous_lunar_lander.ipynb` — Main notebook implementing SAC, training, checkpointing, and evaluation.  
- `sac_lunar_lander_actor_network.pth` — Trained actor network.  
- `c_lunar_lander.mp4` — Video of the trained agent performing landings.  

---

## Training Summary

- The model reached an **average reward of over 200** on the last 100 episodes.  
- **Training duration:** 603 episodes.  
- **Evaluation performance:** Average reward of **247.597** over 50 evaluation episodes.  

> Note: The evaluation was run using a deterministic policy to assess average performance.

---

