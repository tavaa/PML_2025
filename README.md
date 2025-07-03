# PML_2025
This repository collects exercises, homework and a final project created for the **Probabilistic Machine Learning** (PML) course held at the University of Trieste (UniTs) in 2025.

## Introduction
The course introduces the fundamentals of machine learning with a probabilistic approach, combining probability theory, Bayesian inference, generative models, probabilistic neural networks, and advanced methods such as variational autoencoders (VAE) and Gaussian Processes.

## Structure of the Repository
```bash
PML_2025/
├── detection_framework_for_financial_risk_RVAE/  # Final Project
├── homework01/                                    # Exercises on MLE, MAP, sampling
├── homework02/                                    # Exercises related to Bayesian inference and MCMC
└── README.md                                      # Project documentation
```


##  Main contents

### `homework01/`
Introductory exercises on probabilistic learning:
- Estimation of parameters using MLE and MAP
- Sampling and simulation of distributions
- Visual analysis of likelihoods and prior/posterior

###  `homework02/`
Advanced insights:
- Bayesian inference with conjugate models
- MCMC: Metropolis-Hastings and Gibbs Sampling
- Modeling with Gaussian Processes.

###  `detection_framework_for_financial_risk_RVAE/`
Advanced hands-on project:
- Implementation of a **Recurrent Variational Autoencoder** (R-VAE).
- Application to **temporal financial data** for the detection of **risk and anomalies**
- Use of attention (attention) mechanisms and evaluation metrics.

##  Requirements

Make sure you have:

- Python ≥ 3.8  
- Jupyter Notebook  
- Common Python packages:
  - `numpy`, `scipy`, `matplotlib`, `pandas`
  - `torch` or `tensorflow` (for VAE)
  - `seaborn`, `sklearn`.

## Usage

Clone the repository:

```bash
git clone https://github.com/tavaa/PML_2025.git
cd PML_2025
```

Create and Activate a virtual Environment:

```bash
python -m venv venv
source venv/bin/activate   # venv\Scripts\activate on Windows
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

