# heston-pinn-project
A Physics-Informed Neural Network (PINN) approach for option pricing and calibration under the Heston model.
Project under the supervision of Prof. Lu Lu, Yale University.

## Team Members

* Kieran A. Malandain (Yale College '26, Physics, Philosophy, Data Science)
* Hakob Chakhoyan (Yale Math PhD '30)
* Selim Kalici (Yale Astrophysics PhD '30)

## Project Goal

We aim to build fast, differentiable surrogates for European option prices under Heston stochastic-
volatility models using PINNs. The goal is to train a model that is able to accurately and instantaneously price options, compute Greeks via AutoDiff, and efficiently calibrate to real time market data.

## Key Reference Paper

Our methodology is heavily inspired by the state-of-the-art approach detailed in:

> Hainaut, D., & Casas, A. (2024). *Option pricing in the Heston model with physics inspired neural networks*. Annals of Finance. 
> [https://doi.org/10.1007/s10436-024-00452-7](https://doi.org/10.1007/s10436-024-00452-7)
