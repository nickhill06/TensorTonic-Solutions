# 🧠 TensorTonic Solutions

> My personal solutions to ML coding challenges on [TensorTonic](https://www.tensortonic.com) — the LeetCode for Machine Learning.

---

## 🤔 What is TensorTonic?

TensorTonic is a platform where you implement **200+ ML algorithms from scratch** — no scikit-learn shortcuts, no PyTorch magic. Just you, NumPy, and math.

Think of it as LeetCode but instead of binary trees, you're building:
- Neural network layers
- Optimizers (Adam, SGD, RMSProp)
- Activation functions
- Loss functions
- Transformers, BERT, ResNet, GANs...

**Why it exists:** Reading about ML is easy. Actually implementing it? That's where real understanding happens.

---

## 📁 Repo Structure

```
tensortonic-solutions/
│
├── activation-functions/
│   ├── sigmoid.py
│   ├── relu.py
│   └── softmax.py
│
├── optimizers/
│   ├── sgd.py
│   ├── adam.py
│   └── rmsprop.py
│
├── loss-functions/
│   ├── cross_entropy.py
│   └── mse.py
│
├── deep-learning/
│   ├── batch_norm.py
│   ├── dropout.py
│   └── forward_pass.py
│
├── math-stats/
│   ├── softmax.py
│   └── information_gain.py
│
└── README.md
```

---

## ✅ Solutions Tracker

| Problem | Category | Difficulty | Status |
|---|---|---|---|
| Sigmoid | Activation Functions | 🟢 Easy | ✅ Done |
| ReLU | Activation Functions | 🟢 Easy | ⬜ Todo |
| Softmax | Activation Functions | 🟡 Medium | ⬜ Todo |
| SGD | Optimizers | 🟢 Easy | ⬜ Todo |
| Adam | Optimizers | 🔴 Hard | ⬜ Todo |
| Cross Entropy Loss | Loss Functions | 🟡 Medium | ⬜ Todo |
| Batch Normalization | Deep Learning | 🔴 Hard | ⬜ Todo |
| Dropout | Deep Learning | 🟡 Medium | ⬜ Todo |

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **NumPy only** — no sklearn, no torch, no shortcuts
- Vectorized implementations (no Python loops)

---

## 🚀 Quick Example

Here's the simplest one — **Sigmoid**:

```python
import numpy as np

def sigmoid(x):
    x = np.array(x, dtype=float)
    return 1 / (1 + np.exp(-x))
```

```python
sigmoid(0)           # → 0.5
sigmoid([0, 2, -2])  # → [0.5, 0.881, 0.119]
```

That's it. The formula directly in code. No magic, no wrappers.

---

## 🧩 How TensorTonic Problems Work

Each problem gives you:
1. **A formula** to implement
2. **Input/Output examples** to verify
3. **Constraints** (usually: NumPy only, vectorized, no loops)
4. **An interactive visualizer** to see what your function actually does

You write the function → hit submit → instant feedback.

---

## 🎯 Why I'm Doing This

- To actually understand ML math, not just call `.fit()`
- To prep for ML engineering interviews
- To build intuition for what happens inside PyTorch/TensorFlow

---

## 📚 Resources

- 🌐 [TensorTonic Platform](https://www.tensortonic.com)
- 📐 [TensorTonic ML Math Course](https://www.tensortonic.com/ml-math) — free, covers stats, linear algebra, calculus, optimization
- 📖 [NumPy Docs](https://numpy.org/doc/)

---

## ⭐ Star This Repo

If you're also grinding TensorTonic, feel free to reference these solutions — but try the problem yourself first. The whole point is to *build* the understanding.

---

*"Stop reading tutorials. Start implementing algorithms."* — TensorTonic

---

## 👤 Author

**Nikhil Yadav**
- GitHub: [@nickhill06](https://github.com/nickhill06)
