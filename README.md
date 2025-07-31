# AI Agents on a Saddle Surface

This project demonstrates how AI agents follow gradients on a saddle-shaped **Happiness surface**, visualized in 3D. The agents (Carrot, Broccoli, Potato) optimize for two variables: **Taste (T)** and **Health (H)**.

The system shows how the agents ascend the surface using gradient ascent, and visualizes **eigenvectors** of the Hessian at the origin.

---

## 🧠 Concept

- **Happiness Function**:  
  \( S(T, H) = T \cdot H - \frac{1}{2}T^2 - \frac{1}{2}H^2 \)

- **Gradient Ascent**:  
  Agents use gradients to update their positions toward local optima.

- **Eigen Analysis**:  
  Eigenvectors and eigenvalues of the Hessian are used to understand the surface curvature at the origin.

---

## 📊 Visualization

- A **3D surface plot** is generated using `matplotlib`.
- Agents start from different points and climb the surface.
- Eigenvectors are visualized from the origin.
- The animation is saved as a `.gif` file.

<p align="center">
  <img src="ai_agents_eigenvectors_saddle.gif" width="500"/>
</p>

---

## 📁 Files

| File | Description |
|------|-------------|
| `varunteach1.py` | Main Python script containing logic, animation, and eigen analysis |
| `ai_agents_eigenvectors_saddle.gif` | The output animation showing agent motion |
| `README.md` | This file |

---

## 🛠️ Requirements

```bash
pip install numpy sympy matplotlib pillow
```

---

## ▶️ How to Run

```bash
python varunteach1.py
```

The animation will be saved as `ai_agents_eigenvectors_saddle.gif`.

---

## 📬 Author

**Varun Maruthachalam**  
> Exploring AI, optimization, and data visualization  
> GitHub: [Varunmaruthachalam](https://github.com/Varunmaruthachalam)

---

## 🌟 License

MIT License. Feel free to use, share, or modify!
# ai-agents-saddle-surface
AI agents optimizing on a saddle-shaped happiness function
