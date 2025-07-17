
# 🔬 PINNs: Solving & Discovering PDEs using Deep Learning

This repository implements **Physics-Informed Neural Networks (PINNs)** for solving and discovering nonlinear PDEs such as:

- ✅ **Burgers’ Equation** (forward problem)
- ✅ **2D Navier–Stokes Equations** (inverse problem & pressure reconstruction)
- ✅ **Korteweg–de Vries Equation** (sparse temporal snapshots)

These implementations are inspired by the seminal paper:  
📄 *Raissi et al. (2019), Physics-Informed Neural Networks, Journal of Computational Physics*

---

## 📓 Notebooks

- `notebooks/1_Burgers_Equation.ipynb` — Solves Burgers’ equation using continuous-time PINNs
- `notebooks/2_Navier_Stokes_Discovery.ipynb` — Learns λ₁, λ₂ from velocity field and reconstructs pressure field
- `notebooks/3_KdV_Discovery.ipynb` — Learns PDE from two sparse solution snapshots

---

## 📦 Dependencies

Create a virtual environment and install dependencies:

```bash
pip install -r requirements.txt
```

Main libraries:
- `tensorflow` or `jax`
- `numpy`, `scipy`, `matplotlib`
- `streamlit` (for optional interactive interface)

---

## 🚀 Interactive App

You can run a simple interactive visualization using **Streamlit**:

```bash
cd interactive_app
streamlit run app.py
```

Use sliders to change viscosity, collocation points, etc., and visualize solution updates.

---

## 🧠 Concepts Used

- PINNs (Physics-Informed Neural Networks)
- Automatic Differentiation
- Implicit Runge–Kutta Schemes
- PDE Parameter Discovery
- Data-Driven Modeling of Scientific Systems

---

## ✍️ Author

**Praveen R**  
B.Tech Mechanical Engineering, NIT Calicut  
[LinkedIn](#) | [Email](#) | [Project Demo (optional)](#)

---
