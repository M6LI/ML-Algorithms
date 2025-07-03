# ML‑Algorithms

*A personal portfolio project showcasing Python proficiency through from‑scratch implementations of classical machine‑learning algorithms. Only **NumPy** and **Matplotlib** are used for numerical work and visualisation.*

---

## Notebooks at a Glance

| Algorithm                   | Notebook                                                       | What it demonstrates                                                       |
| --------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------------- |
| Linear Regression           | [Linear\_Regression.ipynb](./Linear_Regression.ipynb)          | Closed‑form normal equation, batch gradient descent, synthetic data fit    |
| Logistic Regression         | [Logistic\_Regression.ipynb](./Logistic_Regression.ipynb)      | Binary classification, cross‑entropy loss, decision boundary visualisation |
| k‑Nearest Neighbours        | [kNN.ipynb](./kNN.ipynb)                                       | Lazy learning, distance metrics, effect of *k* on accuracy                 |
| Feed‑forward Neural Network | [Deep Neural Networks.ipynb](./Deep%20Neural%20Networks.ipynb) | Multi‑layer perceptron built from scratch, back‑prop, mini‑batch SGD       |

*(Each notebook is fully self‑contained; no external datasets or helper libraries are required.)*

---

## Running the Notebooks

```bash
# 1. Clone the project
git clone https://github.com/M6LI/ML-Algorithms.git
cd ML-Algorithms

# 2. (Optional) create a virtual environment
python -m venv .venv && source .venv/bin/activate

# 3. Install minimal dependencies
pip install numpy matplotlib jupyter

# 4. Fire up Jupyter
jupyter notebook
```

Run the cells top‑to‑bottom to see the algorithms learn in real‑time.

---

## Repository Layout

```text
ML-Algorithms/
├── Deep Neural Networks.ipynb
├── Linear_Regression.ipynb
├── Logistic_Regression.ipynb
├── kNN.ipynb
└── README.md
```

---

## License

Released under the **MIT License**.

---

> *Built for learning and demonstration!* 🚀
