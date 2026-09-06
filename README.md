# Hi, I'm Bakhtawar 👋

**ML Engineer**, applying diagnostic methods across medical AI and robotics | Open to Relocation

---

## 🎯 What I Do

I look at cases where a model appears to work and doesn't — recent projects span seizure detection from EEG and grounding failures in a robot manipulation policy. My background is in shipping production ML systems; my current focus is figuring out why they break.

- **Medical AI Diagnostics** (clinical signal analysis, seizure detection)
- **VLA & Agentic System Diagnostics**
- **Reinforcement Learning**
- **Applied ML in Production**
---

## 🔬 Research

**eeg-seizure-fusion-probe** *(in progress)*
EEG seizure detection on CHB-MIT, benchmarking a feature-based GBM baseline against fine-tuned EEG foundation models (LaBraM, BENDR, NeuroGPT). Baseline GBM with expanded spectral/wavelet/cross-channel features reaches AUC-PR 0.174 (sensitivity 0.34 @ 34 FA/hr) on a held-out patient split. Currently fine-tuning LaBraM on CHB-MIT to test whether documented epilepsy-detection underperformance in foundation models replicates under a from-scratch pipeline; BENDR and NeuroGPT comparisons planned next.

**vla-grounding-probe**
Mechanistic layer-wise diagnostic of a vision-language-action model on manipulation tasks. Found language embedding similarity running inverse to grounded conditioning predictions in a majority of tested tasks — validated against CLIP-family affirmation bias literature.

**Action Space Design and Policy Optimisation for RL-Based UAV Collision Avoidance** *(MSc thesis, under review — Elsevier)*
Controlled factorial study (PPO vs. SAC × 3 action spaces × 3 reward densities, 54 runs) diagnosing SAC's catastrophic failure on hybrid action spaces, traced to its entropy auto-tuning mechanism.

**Multimodal Agentic RL System**
FiLM vs. concat fusion comparison in MiniGrid — naive concatenation caused language to be ignored (55% instruction-following), FiLM improved to 67–90%, but 0% on novel unseen instructions. Confidence scores found uninformative.

---

## 🚀 Applied Work

**Lexis** — Production-grade AI document intelligence platform combining a full RAG pipeline, conversational research agent, and policy document assistant for government/enterprise use.

**Sakeenah** — AI-assisted journaling platform (founder), live at [sakeenah-journal.vercel.app](https://sakeenah-journal.vercel.app/), ~20 active users.

**QuantVol** — Time-series forecasting system for equity volatility, benchmarking econometric models against ML/deep learning approaches.

---

## 🛠️ Tech Stack

- **ML & Modeling:** PyTorch, Scikit-learn, XGBoost, TensorFlow, Stable-Baselines3
- **LLM & Agentic Systems:** LangChain, LangGraph, LangSmith, RAG, Prompt Engineering
- **Vision & Robotics:** SmolVLA, LIBERO, YOLO, OpenCV, ROS2, Gazebo
- **MLOps:** FastAPI, Docker, AWS, GCP, MLflow, CI/CD
- **Data:** Pandas, NumPy, SPSS, Power BI

---

## 📝 Publications

- Iftikhar, B., Ahmad, R., Ghafoor, S., & Qazi, S. *Action Space Design and Policy Optimisation for Reinforcement Learning-Based UAV Collision Avoidance in Post-Earthquake Environments.* Under review, Elsevier.
- Iftikhar, B. et al. (2020). *Cost-effective, Reliable, and Precise Surface Mount Device (SMD) on PCBs.* IOP Conference Series: Materials Science and Engineering.

---

## 🎯 Currently

Focused on exploring opportunities in health-tech and medical AI. Also open to research assistant roles and AI strategy consulting.

---

## 📫 Connect

- LinkedIn: [linkedin.com/in/bakhtawar-iftikhar](https://www.linkedin.com/in/bakhtawar-iftikhar/)
- Portfolio: [bakhtawar-iftikhar.base44.app](https://bakhtawar-iftikhar.base44.app/)
- Email: bkifti98@gmail.com

---

> Interested in why AI systems fail quietly, not just whether they work.
