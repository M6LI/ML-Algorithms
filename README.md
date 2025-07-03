# ML-Algorithms
*A from‑scratch mini‑library of classical machine‑learning algorithms implemented in pure Python with **NumPy** for math and **Matplotlib** for visualisation.*

---

## Table of Contents

1. [Implemented Algorithms](#implemented-algorithms)
2. [Quick Start](#quick-start)
3. [Repository Structure](#repository-structure)
4. [Contributing](#contributing)
5. [License](#license)

---

## Implemented Algorithms

| Algorithm                        | Notebook                                                       | Highlights                                                                       |
| -------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| Linear Regression                | [Linear\_Regression.ipynb](./Linear_Regression.ipynb)          | Normal‑equation & batch gradient descent solutions, synthetic data demo          |
| Logistic Regression              | [Logistic\_Regression.ipynb](./Logistic_Regression.ipynb)      | Binary classification, cross‑entropy loss, decision boundary plot                |
| k‑Nearest Neighbours             | [kNN.ipynb](./kNN.ipynb)                                       | Distance metrics, hyper‑parameter *k* sweep, toy 2‑D dataset                     |
| Feed‑forward Deep Neural Network | [Deep Neural Networks.ipynb](./Deep%20Neural%20Networks.ipynb) | Multi‑layer perceptron built from first principles, mini‑batch SGD, ReLU/Softmax |

> *More notebooks coming soon — feel free to open an issue or PR with suggestions!*

---

## Quick Start

### 1. Clone & set up an environment

```bash
# Clone the repo
git clone https://github.com/M6LI/ML-Algorithms.git
cd ML-Algorithms

# (Optional) create a virtual environment
python -m venv .venv && source .venv/bin/activate

# Install the only dependencies
pip install --upgrade pip
pip install numpy matplotlib jupyter
```

### 2. Launch the notebooks

```bash
jupyter notebook
```

Open any notebook from the list above and run the cells top‑to‑bottom. Each notebook is **self‑contained** and generates its own synthetic data, so no external datasets are required.

---

## Repository Structure

```text
ML-Algorithms/
├── Deep Neural Networks.ipynb
├── Linear_Regression.ipynb
├── Logistic_Regression.ipynb
├── kNN.ipynb
└── README.md
```

---

## Contributing

1. **Open an issue** describing the bug/improvement/algorithm you’d like to add.
2. **Fork** the repo and create a feature branch.
3. Keep the style simple & readable; run all cells to ensure the notebook executes without errors.
4. **Submit a pull request** — feedback and collaboration are welcomed!

---

## License

Released under the **MIT License**. Feel free to swap it for another OSI‑approved license if it better suits your needs.

---

*Happy learning / hacking!* 🚀
