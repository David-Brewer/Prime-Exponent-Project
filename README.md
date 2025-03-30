# Prime-Exponent-Project
ML project exploring the relationship between integers and the module space formed on the exponents of prime factors.  Is there another way of finding an integer's prime factors without explicitly factoring the integer?
# Prime Exponent Module – Learning Arithmetic Structure with Machine Learning

##Overview

This project explores a unique intersection of **number theory** and **machine learning**: representing integers as tuples of prime exponents (what we call **prime exponent vectors**) and investigating whether a machine learning model can learn the underlying structure of multiplication from these representations.

Every positive integer can be uniquely factored into a product of prime powers:
\[
n = p_1^{e_1} \cdot p_2^{e_2} \cdot \ldots \cdot p_k^{e_k}
\]
Fixing an order on the primes, we encode each integer as a vector of exponents \( \vec{e} \in \mathbb{Z}^k \). In this space, multiplication becomes addition, and division becomes subtraction — turning multiplicative arithmetic into linear structure.

> **Note:** Mathematically, this is a **free ℤ-module**, not a vector space over a field. We use the term **"vector"** throughout this project for readability and connection to machine learning conventions.

---

##Goal

The goal is to train a machine learning model to learn the mapping: prime exponent vector -> integer.  The catch is we want the ML model to learn the mapping *without* performing any arithmetic operations.  We are attempting to sidestep the enormous hurdle of factoring large integers.

## Getting Started

### Files
- `prime_exponent_dataset.pdf` – PDF version of the main notebook
- `prime_exponent_dataset.csv` – Sample output dataset
- `prime_exponent_dataset.ipynb` - Jupyter notebook containing Python code for generating the dataset

### How to Run
To reproduce the dataset:
1. Install required packages (also listed in `requirements.txt`):  
pip install pandas numpy sympy matplotlib
2. Run the Jupyter notebook (`prime_exponent_dataset.ipynb`)
3. Adjust vector length, number of samples, and exponent range as needed

The dataset will be saved as `prime_exponent_dataset.csv` and visualizations will display inline.
