# ANN Implementation using Pyrenn-LM Method

This repository contains a Jupyter Notebook that implements an Artificial Neural Network (ANN) using the **Pyrenn** library and the Levenberg-Marquardt (LM) optimization method. The project demonstrates loading a dataset, preprocessing data, training an ANN, and evaluating its performance using custom metrics.

## Features
- Loading and preprocessing of biosensor data.
- Splitting data into training and test sets.
- Feature standardization using `StandardScaler`.
- ANN creation and training using `Pyrenn`.
- Custom metrics for evaluating performance, including Normalized Root Mean Square Error (NRMSE) and leverage adjustments.
- Option for K-Fold cross-validation.

## Installation

To run this project, install the required Python libraries:

```bash
pip install pyrenn pandas numpy matplotlib scikit-learn
