PathMNIST Federated Learning: FedAvg vs FedProx

This project implements and compares two federated learning algorithms, FedAvg and FedProx, on the PathMNIST medical image dataset using PyTorch.

The experiment uses:

- 5 federated clients
- Non-IID data distribution using Dirichlet alpha = 0.3
- 40% label noise applied to one client
- FedAvg and FedProx aggregation methods

The project evaluates global model accuracy and individual client accuracy. It also tracks training loss and client update metrics to study the performance of both algorithms under heterogeneous data conditions.

Objective: To compare the performance and robustness of FedAvg and FedProx in a non-IID federated medical image classification setting.
