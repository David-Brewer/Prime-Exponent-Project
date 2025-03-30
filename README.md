# Prime-Exponent-Project
ML project exploring the relationship between integers and the module space formed on the exponents of prime factors.  Is there another way of finding an integer's prime factors without explicitly factoring the integer?
# Prime Exponent Module – Learning Arithmetic Structure with Machine Learning

##Overview

This project explores a unique intersection of **number theory** and **machine learning**: representing integers as tuples of prime exponents (what we call **prime exponent vectors**) and investigating whether a machine learning model can learn the underlying structure of multiplication from these representations.

Here's a LaTeX document that details the math behind the idea:
[Prime_Exponents.pdf](https://github.com/user-attachments/files/19527342/Prime_Exponents.pdf)



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

Please feel free to reach out with any thoughts, questions, or constructive feedback:
[LinkedIn][www.linkedin.com/in/dbbrewer]
