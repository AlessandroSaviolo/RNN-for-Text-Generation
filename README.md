# Recursive Neural Network for Text Generation

This project is part of a series of projects for the course _Deep Learning_ that I attended during my exchange program at National Chiao Tung University (Taiwan). See `task.pdf` for the details of the assignment. See `report.pdf` for the report containing the representation and the analysis of the produced results.

The purpose of this project is to implement a Recursive Neural Network for Text Generation.

## 1. Dataset

- [Shakespeare Training Data](https://drive.google.com/open?id=1QxvfgPHqLaFazKjGnvFkYZLG9IPq2zts)

- [Shakespeare Validation Data](https://drive.google.com/open?id=1ifCayXQxv0-iOh0V3wEdgKtl1VU-AevO)

## 2. Project Structure

- `main.py` : main function, use it to change task ('r' or 'c') and hyperparameters (i.e., learning rate, number of epochs)

- `model.py` : contains the regression and classification neural network models

- `regression.py` : run regression using the relative model from model.py, use it to change the hyperparameters of the model (i.e., number of neurons)

- `classification.py` : run classification using the relative model from model.py, use it to change the hyperparameters of the model (i.e., number of neurons)

- `utilities.py` : contains plot functions and common functions among the different files (i.e., load dataset which is used both for regression and classification)

- `deep_classification.py` : deep classifier used to plot the distribution of latent features at different training stages. It contains also the deep model
